##### stsc.algorithms.stock.patterns
 * TrianglePattern
```
{ {1: DoubleSignal, 2: DoubleSignal},
e -> [Integer: size (2 by default)],
e -> [Double: L (0.5 by default), XF (2.0 by default), XT (5.0 by default), STC (-0.05 by default), LTC (0.05 by default)] }
-> DoubleSignal.
```
 * WedgePattern
```
{ {1: DoubleSignal, 2: DoubleSignal},
e -> [Integer: size (2 by default)],
e -> [Double: L (0.5 by default), XF (2.0 by default), XT (5.0 by default), STC (-0.05 by default), LTC (0.05 by default)] }
-> DoubleSignal.
```
 * StockMarketCycle
```
{ {},
e -> [Integer: smaSmallSize (15 by default)],
e -> [Double: smasDiv (1.5 by default), divDiff (0.01 by default), divSmallDiff (0.0 by default)] }
-> DoubleSignal.
```
