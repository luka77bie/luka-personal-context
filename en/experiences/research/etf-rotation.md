# Independent narrative-aware ETF rotation

[Home](../../README.md) · [简体中文](../../../zh/experiences/research/etf-rotation.md)

On 17 November he explained the test as asking whether attention distinguished future returns among ETFs with similar price momentum. Across four walk-forward folds, the 60-day momentum baseline and attention model returned 22.21% and 21.46% annualised, with Sharpe ratios of 0.859 and 0.838 respectively. He kept the baseline. His first check remains unknown, and the immediate psychological reaction is not independently supported; do not add one. ETF-001 and ETF-002. [Project results](https://github.com/luka77bie/narrative-aware-etf-rotation#walk-forward-out-of-sample-evaluation)

**Scope.** Independent quantitative research. See [Founder Securities](../internships/founder.md) for the earlier placement exploration. Sources SRC-CV, SRC-ADVISOR and SRC-ETF-REPO. Claim ETF-001.

**Question.** Do market-attention proxies add stable information or improve a strategy beyond 60-day momentum?

**Work.** Materials report that he extended a Python framework after the placement. It tested monthly equal-weight top-three rotation, next-trading-day execution and transaction costs, with full-sample, subperiod and four-fold walk-forward comparisons. Verify the exact configuration and output against a repository version or run.

**Result and decision.** The attention specification performed better over the full sample. Its advantage did not hold across the walk-forward evaluation, so he retained MOM60 as the main specification.

**Scope of results.** Research and paper trading support conclusions within this test design. Verify attribution, costs, universe and fold results before formal use. The comparison alone establishes neither universal signal failure nor live profitability.

**Open details.** Which result did he check first? How did he weigh overfitting? Which run or report reproduces the decision?

**Individual contribution.** He independently extended the study after the placement. Check code and runs for the contribution behind any specific result.

**Assistance and independent explanation.** AI assistance awaits confirmation. Be ready to explain MOM60, costs, walk-forward evaluation and the data universe.
