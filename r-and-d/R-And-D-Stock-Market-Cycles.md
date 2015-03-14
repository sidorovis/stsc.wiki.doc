
# Stock Market Cycles R&D

The goal of this research is to find correct algorithms call order to recognize common market cycles (6-th years cycles).

### Using .Sma with big N period

![](https://github.com/sidorovis/stsc/wiki/images/r_and_d/issues_58/sma_on_spy_with_different_N.png)

### Uniting different sma's:
 * initializeSmaAlgo(75, init);
 * initializeSmaAlgo(100, init);
 * initializeSmaAlgo(125, init);
 * initializeSmaAlgo(250, init);
 * initializeSmaAlgo(300, init);
 * initializeSmaAlgo(400, init);
 * initializeSmaAlgo(500, init);
 * smallSma = createSmaAlgo(smallSmaName, smaSmallSize (for example 5), init);

![](https://github.com/sidorovis/stsc/wiki/images/r_and_d/issues_58/sma_on_stock_market_cycle_for55_smaSmall.png)

### Using Average on Sma with big periods and Sma with small period (StockMarketCycle).

##### smcEquityTest.loadLine = .StockMarketCycleEquity(PSS=10i, OLB=60d, OSB = -60d, .Sma(N=50i, .StockMarketCycle() ) )

![](https://github.com/sidorovis/stsc/wiki/images/r_and_d/issues_58/equity_for_60_m60_sma50.png)

