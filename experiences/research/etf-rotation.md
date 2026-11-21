# 独立 Narrative-Aware ETF Rotation

**类型**：独立量化研究。实习期间的探索见 [Founder](../internships/founder.md)。来源 SRC-CV、SRC-ADVISOR、SRC-ETF-REPO。主张 ETF-001。

**问题**：market-attention proxies 是否在 60 日动量以外带来稳定的解释或策略改进？

**个人工作**：申请材料记载在实习后扩展 Python 框架，比较按月等权 Top-3 ETF 轮动、次交易日执行与交易成本设定，加入 full-sample、subperiod 与四段 walk-forward OOS 比较。精确配置与输出应对应 GitHub 版本或运行记录。

**关键结果和决定**：较复杂的 market-attention 规格在全样本表现更好，整体 walk-forward 下没有保持相同优势。本人保留 MOM60 作为主要研究规格。

**边界**：研究与 paper-trading 观察只支持该测试设计内的结论。成果归属、成本、数据范围、四段结果均应在正式使用前核对。该结果无法单独证明 attention 信息普遍无效或实盘获利。

**待补**：第一次看到 OOS 结果时你先查了什么？取舍时怎样考虑 overfitting？具体哪个结果或报告能复现这个决定？
