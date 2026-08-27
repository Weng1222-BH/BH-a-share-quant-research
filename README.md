# BH-a-share-quant-research
A-share quantitative research project covering data analysis, strategy backtesting, factor research, machine learning and paper trading.

## 项目目标

从零学习 A 股量化，逐步完成数据分析、策略回测、科学验证、因子研究、机器学习预测、模拟盘验证，并形成可追溯的 GitHub 与简历成果。

当前工具主线为 **Python + AKShare + RQAlpha**；后期按研究需要引入 Qlib，暂不提前引入复杂交易系统。工具的角色、可用性与版本在实际使用前核验，不把计划中的工具写成已安装或已验证。

## 从哪里开始

- [真实学习进度](docs/progress.md)：项目唯一真实学习进度源；继续学习前先读这里。
- [主线路线图](docs/roadmap.md)：Stage 0–7 的目标与动态拆分原则。
- [教学与运行规则](docs/operating_principles.md)：Session、Gate、Transfer Task 和路线复核规则。
- [想法积压清单](IDEA_BACKLOG.md)：旁支问题与未来研究方向，不等于当前任务。

当前 Stage、Substage、Session、下一任务及测验和模拟盘状态仅在 progress.md 维护；本页不重复维护进度快照。

## 学习方式

采用 **Stage → Substage → Session → Gate**。每个 Stage 根据学习结果动态拆分约 2–4 个 Substage，每个 Substage 包含若干 Session；Gate 是 Substage 结束时的正式验收。不要一次性固定 Stage 0–7 的全部微观计划。

Session 默认采用 **引子 → 案例 → 必要知识 → 实践 → 复盘**。通过问题、案例、预测、诊断和实操暴露认知缺口，再补充当前任务所需知识，避免持续单向讲授。

Session 内使用短即时检查；每个 Substage 的正式 Gate 覆盖概念理解、机制解释、实际操作和新情境迁移。第一次正式测验难度由教学模型根据此前表现确定；之后每次正式测验前先询问希望相较上一次“降低 / 保持 / 提高”，再结合上一轮测验、实操与迁移表现决定实际难度，题目不得超出教学进度。

每次 Substage Gate 完成后，必须当时实时检索并选择 1 个与 Stage 0 至当前 Substage 已学内容直接相关、值得研究的最新外部材料，配套简短 Transfer Task。下一次 Session 开始时先检查其完成和应用情况，再进入新知识。

旁支疑问按必要性处理：当前任务必需的当场解决；相关但非必要的简要解决、在当前学习记录留痕后返回主线；未来研究方向简要解释后写入 IDEA_BACKLOG.md。不得因旁支问题无故改变主线。

## 主线与调整

Stage 0 量化世界观 → Stage 1 A股数据与基础收益分析 → Stage 2 第一套完整策略与回测 → Stage 3 科学回测与偏差识别 → Stage 4 因子研究 → Stage 5 多因子与机器学习预测 → Stage 6 模拟盘验证 → Stage 7 GitHub 与简历成果整理。

这是一条可调整的主线框架。进入重要 Substage/Stage 前，根据学习成果、研究结果、项目目标、工具与数据条件、最新量化实践及当前 AI 模型与工具能力重新评估路线。核心模型或工具能力明显升级时，保留仍然正确的已确认内容，只修改必要部分并记录原因。

## 仓库结构

| 路径 | 用途 |
| --- | --- |
| README.md | 项目目标、入口与规则摘要 |
| IDEA_BACKLOG.md | 待深入问题与研究想法 |
| docs/roadmap.md | 宏观路线和动态规划 |
| docs/progress.md | 唯一真实学习进度源、当前任务与决策记录 |
| docs/operating_principles.md | 教学、测验、迁移与维护规则 |
| notebooks/ | 后续探索性分析与学习笔记 |
| src/ | 后续可复用研究与回测代码 |
| reports/ | 后续研究报告、Session、Gate 与 Transfer Task 产物 |
| paper_trading/ | 后续模拟盘记录与结果 |

四个后续目录中的 .gitkeep 仅用于保留空目录，不代表已有代码、研究成果或模拟盘活动。本次初始化不创建实际策略代码，也不提前执行 Stage 0 教学。

## 项目事实优先级

**GitHub 实际代码/结果 > docs/progress.md > 研究报告与 Session 产物 > 聊天记录 > 模型记忆**

发现冲突时先核验实际证据，再更新 progress.md 及受影响文档，并记录原因。计划、想法和模型记忆不能充当完成证据；可运行代码本身也不能证明学习者已理解或通过 Gate。
