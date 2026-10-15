# Research Paper Workflow

> 从选题到论文交付，把当前科研问题转成有依据、可检查、能接续的下一步。

Research Paper Workflow 是一套面向 Codex 的中文科研流程 Skill。你可以从零讨论研究方向，也可以带着现有数据、方案、图表或初稿直接进入当前任务。它按研究类型和现有材料选择相关节点，覆盖 15 条科研主线；每个课题只使用实际需要的部分。

**当前版本：v0.1** · [下载 Skill ZIP](https://github.com/KennethParkerWang/research-paper-workflow/releases/download/v0.1/research-paper-workflow-v0.1.zip) · [查看发布说明](https://github.com/KennethParkerWang/research-paper-workflow/releases/tag/v0.1)

## 它能帮你做什么

- **明确研究方向**：从意愿、资源和目标出发，形成候选问题，核查文献邻近工作、拟贡献和初步可行性；逐轮讨论选题、目标假说与目标期刊。
- **设计研究与取得证据**：把问题转成方法、证据要求、计划、资源和实际取证安排，并根据定量、质性、理论、档案或证据综合等路线调整深度。
- **把结果写成论文**：区分分析结果与允许的结论，组织论证、正文、图表、公式和引文；[论文图件制作模板](18-按模板编写论文/论文图件制作模板.md)支持整组图规划、示意参考生图和真实数据结果图。
- **修改与审查**：处理空泛、模板化或翻译腔表达，研判投稿经验，独立检查主张与证据，按问题根因修订并交付可接续的研究包。

研究过程中会按实际领域和目标期刊继续查阅外部方法、Skill、论文与官方要求，包内手册是工作入口，不是封闭资料库。

## 快速开始

1. 下载并解压 [v0.1 ZIP](https://github.com/KennethParkerWang/research-paper-workflow/releases/download/v0.1/research-paper-workflow-v0.1.zip)，得到 `research-paper-workflow/` 文件夹。
2. 将该文件夹放入 Codex 的用户级 `~/.codex/skills/`，或当前项目的 `.codex/skills/`。Windows 用户级目录为 `%USERPROFILE%\.codex\skills\`；确认最终存在 `research-paper-workflow/SKILL.md`。[Codex Skills 官方示例](https://developers.openai.com/blog/eval-skills)说明了这些目录及显式调用方式。
3. 打开新的 Codex 对话，输入 `$research-paper-workflow`，再说明你现在需要完成的事和已有材料。

可以从这些请求开始：

```text
$research-paper-workflow 我还没有题目。先了解我的兴趣、目标和资源，再逐步讨论研究方向。
$research-paper-workflow 我已有研究方案和一部分数据。请从当前材料判断下一项最有价值的工作。
$research-paper-workflow 请为这篇初稿规划主图与补图；示意图做重绘参考，结果图依据真实数据和代码。
$research-paper-workflow 只审查这段结果与结论是否一致，并指出需要回到哪一步修正。
```

## 工作方式

| 当前需要 | Skill 怎样接入 |
|---|---|
| 从零启动 | AI提出有依据的候选与取舍，用户分别确认选题、核心假说和目标期刊。 |
| 接续已有研究 | 先核现有材料与决定的有效范围，直接进入相关阶段；有效成果继续复用。 |
| 只处理局部 | 一张图、一段文字、一次结果解释都可以单独进入，补足该任务真正需要的前提。 |
| 证据或方案变化 | 找到最早受影响的输入或决定，更新受影响成果和下游稿件，再复核当前结论。 |

真实研究的启动方案及其实质变化由用户确认。统计、理论、质性和其他研究路线按各自证据标准判断；漂亮图文或工具运行成功不能替代科学依据。

## 文档入口

- [SKILL.md](SKILL.md)：按任务选择阶段和能力节点。
- [完整流程](docs/workflow-design.md)：15 条主线与条件分支。
- [共用交接规则](00-阶段交接关系/阶段交接关系.md)：确认、单项任务、验收、回退和材料衔接。
- [选题模块](01-选题要求与确认/research-topic-selection/topic-selection.md)：从零进入研究问题。
- [论文图件制作模板](18-按模板编写论文/论文图件制作模板.md)：图组规划、领域图例研究、配色、示意参考稿与数据结果图。

这是流程与方法指导。具体课题中的文献事实、材料质量、方法适用性、期刊规则和最终科学判断，仍须依据当时的原始资料核定。v0.1 的发布包保留在 [Releases](https://github.com/KennethParkerWang/research-paper-workflow/releases/tag/v0.1)；仓库后续文档更新不会自动改变已发布的 ZIP。
