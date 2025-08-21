# claue-code-study


1、为claude-code添加/spec命令：拷贝`~/.claude/commands/spec.md`文件，参考文章：[Claude Code + Kiro Spec：别急着生成代码，先让AI理解你的需求](https://mp.weixin.qq.com/s?__biz=MzE5ODE2ODI1Mw==&mid=2247483730&idx=1&sn=1dbcf6b734478daa66204bfadb67164a&source=41&poc_token=HEaDpmij-vqgeJBG7t-iOavw87Fmu0xG3fhU5yIC)



2、cc体验下来规范的文件化读档和归档很有必要。分享reddit上看到的一个方案（我稍微改动了一下）：

**Foundation（基础层）**：存放项目稳定且核心的文档和知识沉淀，每类文档通常仅一份。例如项目愿景、整体架构设计、技术规范、编码标准等。这些文档变更频率低，作为团队共识的权威信息，确保各阶段都有可靠参考。

**Context（上下文层）**：存放项目动态上下文信息，随开发进展持续更新。例如阶段状态记录（stage.md）、当前开发焦点（focus.md）、待办事项清单（todo.md）、决策记录（decisions.md）、活动日志（activity.log）、任务执行日志（tasks.log）等。这些文档反映项目实时状态和过程，使团队随时掌握当前进度与问题，全局上下文清晰透明。多数上下文层文档由工具自动生成或更新（如日志），保持对实际活动的持久记录。

**Components（组件层）**：存放各功能模块的详细文档，每个模块对应独立文件，通常通过模板生成。例如 module-*.md 记录模块的设计与实现细节，api-*.md 描述接口规范，test-*.md 记录模块的测试方案等。组件层文档按需创建和维护，确保模块化开发中每个模块都有配套文档，从而降低模块耦合度，防止知识遗失。


