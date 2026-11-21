# Greater Boston 住房价格回归

**类型与范围**：Manchester Applied Statistics coursework，2025/26，个人项目。来源 SRC-CV、SRC-CORNELL-SOP。主张 HOU-001。

**研究问题**：152 个 Greater Boston towns 的房价与学校资源之间有何统计关联？比较 per-pupil expenditure 和 class size 的关系在增加控制变量后是否稳定。

**个人工作**：在 R 里清理和探索数据，对右偏变量作 log transformation，建立三组 nested OLS。控制因素包括收入、教育、税收、距离等。比较系数、标准误、显著性、模型拟合与残差。CV 记录最大 VIF 为 2.96，引用该数值前先查报告。

**解释边界**：观察数据和这些诊断只支持相应的条件相关性。CV 和草稿中的课程代码、项目分和 module 分在对外引用前查 [冲突清单](../../facts/conflicts.md)。

**本人补充**：最初预期哪个变量关系更稳定？哪一个系数变化让你停下来检查？如果重做，会改变数据或识别设计的哪一步？

**Personal ownership**：个人课程项目，资料记录本人负责 R 数据处理及 nested OLS 和诊断。回到报告核对变量和结果。

**AI assistance and explainability**：AI 辅助情况待确认。准备讲清模型嵌套、控制选择、VIF 与因果边界。
