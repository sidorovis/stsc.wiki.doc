Welcome to the Stsc wiki!

[Main project page](https://github.com/sidorovis/stsc)

Stsc is a bunch of tools to create algorithmic trading strategies. 

This is a complicated system that require you to be familiar with several topics in algorithm trading.

***

### Modules

##### stst.algorithms
##### stsc.common
##### stsc.distributed.hadoop
##### stsc.frontend.zozka
##### stsc.general
##### stsc.integration.tests
##### stsc.news.feedzilla.downloader
##### stsc.news.feedzilla.sqlite.migrations
##### stsc.news.feedzilla.storage
##### stsc.performance
##### stsc.signals
##### stsc.stocks.yahoo.core
##### stsc.stocks.yahoo.downloader
##### stsc.stocks.yahoo.liquidator
##### stsc.storage

***

### Workflow

Workflow for generating algorithmic strategies includes next phases:

1. Creation of hypothesis using simple or complex indicators / factors for different stocks and stock ensembles.

2. Algorithm code realization (probably you will use already created base).

3. Algorithm tuning with possibility to distribute and add parallelism to that process (using Hadoop calculation cluster) (probably also spark or whatever in future).

4. Algorithm testing.

### R&D 

1. [R&D Stock Market Cycles](https://github.com/sidorovis/stsc/wiki/R-And-D-Stock-Market-Cycles)

2. [R&D Support And Resistance Level](https://github.com/sidorovis/stsc/wiki/R-And-D-Support-And-Resistance-Level)


