##### stsc.algorithms.stock.indices.primitive
 * Diff
```
{ {1: DoubleSignal, 2: DoubleSignal}, 
e -> [Integer: size (2 by default) ]} 
-> DoubleSignal.
```
 * Dma
```
{ {1: DoubleSignal}, 
e -> [Integer: size (2 by default); ]
e -> [Double: P (0.2 by default); ] } 
-> DoubleSignal.
```
 * Ema
```
{ {1: DoubleSignal}, 
e -> [Integer: size (2 by default); ]
e -> [Double: P (0.2 by default); ] } 
-> DoubleSignal.
```
 * Level
```
{ {1: DoubleSignal}, 
e -> [Double: f (0.0 by default) ]} 
-> SideSignal.
```
 * SeveralLastMax
```
{ {1: DoubleSignal}, 
e -> [Integer: size (2 by default), N (9 by default); ]} 
-> DoubleSignal.
```
 * SeveralLastMin
```
{ {1: DoubleSignal}, 
e -> [Integer: size (2 by default), N (9 by default); ]} 
-> DoubleSignal.
```
 * Sma
```
{ {1: DoubleSignal}, 
e -> [Integer: size (2 by default), N (5 by default); ]} 
-> DoubleSignal.
```
 * SmStDev
```
{ {1: DoubleSignal, 2: DoubleSignal}, 
e -> [Integer: size (2 by default), N (5 by default); ]} 
-> DoubleSignal.
```
 * Tma
```
{ {1: DoubleSignal}, 
e -> [Integer: size (2 by default); ]
e -> [Double: P (0.2 by default); ] } 
-> DoubleSignal.
```
