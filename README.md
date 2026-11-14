# 新项目信息系统 Skill

用同一套方法建立新项目的资料结构、职责边界和协作规则。适用于只有初步想法的新项目，也适用于已有文档但需要增加领域、拆分平台或梳理交接的项目。

## 开始使用

将 [`initializing-project-information-system/`](initializing-project-information-system/SKILL.md) 整个目录加入你的工具可发现的 Skill 位置，保留其中的 `references/`。在目标项目的会话中调用 `$initializing-project-information-system`，说明项目目标、已有资料和本次是直接搭建还是先讨论。也可以直接向会话提供 [SKILL.md](initializing-project-information-system/SKILL.md) 与同目录的参考文件。

> 用 $initializing-project-information-system 在当前目录建立一个小型排班工具的项目信息系统。目标用户是志愿者，功能范围待定。先搭最小协作骨架，把需要确认的产品规则写进待定项。

Skill 会根据本次职责确定文档范围。通用入口维护项目现状、决策来源和各领域的链接，具体工作只读取相关规范。后续可以按需增加营销、独立平台、质量验收或发布等职责。

- [初始化与目录骨架](initializing-project-information-system/references/intake-and-layout.md)
- [领域职责与工作准则](initializing-project-information-system/references/domain-playbooks.md)
- [多会话、独立平台与版本收尾](initializing-project-information-system/references/ongoing-collaboration.md)
