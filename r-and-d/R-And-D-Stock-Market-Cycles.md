
# Stock Market Cycles R&D

The goal of this research is to find correct algorithms call order to recognize common market cycles (6-th years cycles).

### Using .Sma with big N period

![](https://github.com/sidorovis/stsc/wiki/images/r_and_d/issues_58/sma_on_spy_with_different_N.png)

### Using Average on Sma with big periods and Sma with small period (StockMarketCycle).

##### smcEquityTest.loadLine = .StockMarketCycleEquity(PSS=10i, OLB=60d, OSB = -60d, .Sma(N=50i, .StockMarketCycle() ) )

![](https://github.com/sidorovis/stsc/wiki/images/r_and_d/issues_58/equity_for_60_m60_sma50.png)
