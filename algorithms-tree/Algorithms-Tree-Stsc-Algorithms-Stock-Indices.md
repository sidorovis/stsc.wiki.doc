##### stsc.algorithms.stock.indices
 * Cci
```
{ {no_input}, 
e -> [Integer: size (2 by default); ]
e -> [Double: K (by default 1.0/0.015), N (5 by default)] } 
-> DoubleSignal.
```
 * MarketTrend
```
{ {no_input},
e -> [Integer: size (2 by default); ]
e -> [String: SN (by default 'spy') ] }
-> DoubleSignal.
```
 * MaxForNDays
```
{ {1: DoubleSignal;}, 
e -> [Integer: size (2 by default), P (5 by default), SP (5 by default)] } 
-> DoubleSignal.
```
 * MinForNDays
```
{ {1: DoubleSignal;}, 
e -> [Integer: size (2 by default), P (5 by default), SP (5 by default)] } 
-> DoubleSignal.
```
 * Momentum
```
{ {1: DoubleSignal;}, 
e -> [Integer: size (2 by default), N (5 by default)] } 
-> DoubleSignal.
```
 * OnBalanceVolume
```
{ {1: DoubleSignal;}, 
e -> [Integer: size (2 by default), N (5 by default)] } 
-> DoubleSignal.
```
 * RateOfChange
```
{ {1: DoubleSignal;}, 
e -> [Integer: size (2 by default), N (5 by default)] } 
-> DoubleSignal.
```
 * ResistanceLevel
```
{ {1: DoubleSignal;},
e -> [Integer: size (2 by default), N (8 by default), M (66 by default)],
-> DoubleSignal.
```
 * StochasticOscillator
```
{ {no_input}, 
e -> [Integer: size (2 by default), P (5 by default), SP (0 by default)] } 
-> DoubleSignal.
```
 * StockMarketCycle
```
{ {no_input},
e -> [Integer: smaSmallSize (15 by default)],
e -> [Double: smasDiv (1.5 by default), divDiff (0.01 by default), divSmallDiff (0.0 by default)] }
-> DoubleSignal.
```
 * SupportLevel
```
{ {1: DoubleSignal;},
e -> [Integer: size (2 by default), N (8 by default), M (66 by default)],
-> DoubleSignal.
```
 * Trix
```
{ {1: DoubleSignal}, 
e -> [Integer: size (2 by default); ] } 
-> DoubleSignal.
```
 * TypicalPrice
```
{ {no_input},
e -> [Integer: size (2 by default) ]}
-> DoubleSignal.
```
