On Stock Algorithms tree:

##### [stsc.algorithms(common)](https://github.com/sidorovis/stsc/wiki/Algorithms-Tree-Stsc-Algorithms(Common))

##### [stsc.algorithms.eod.indices.adl](https://github.com/sidorovis/stsc/wiki/Algorithms-Tree-Stsc-Algorithms-Eod-Indices-Adl)

##### [stsc.algorithms.eod.primitive](https://github.com/sidorovis/stsc/wiki/Algorithms-Tree-Stsc-Algorithms-Eod-Primitive)

##### [stsc.algorithms.stock.geometry](https://github.com/sidorovis/stsc/wiki/Algorithms-Tree-Stsc-Algorithms-Stock-Geometry)

##### [stsc.algorithms.stock.indices.primitive](https://github.com/sidorovis/stsc/wiki/Algorithms-Tree-Stsc-Algorithms-Stock-Indices-Primitive)

##### stsc.algorithms.stock.indices
 * Cci
```
{ {no_input}, 
e -> [Integer: size (2 by default); ]
e -> [Double: K (by default 1.0/0.015), N (5 by default)] } 
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
 * StochasticOscillator
```
{ {no_input}, 
e -> [Integer: size (2 by default), P (5 by default), SP (0 by default)] } 
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

TODO End of day primitive (test-like) algortihms (with positions and auto monitoring).
##### stsc.algorithms.stock.indices.adi
 * AdiClv
```
{ {no_input}, 
e -> [Integer: size (2 by default) ]} 
-> DoubleSignal.
```
 * AdiAccDist
```
{ {no_input}, 
e -> [Integer: size (2 by default) ], 
e -> [Double: K (0.0001 by default) ]}
-> DoubleSignal.
```

##### stsc.algorithms.stock.indices.adx
 * AdxAdx
```
{ {no_input}, 
e -> [Integer: N (14 by default), nSma (14 by default), size (2 by default) ]} 
-> DoubleSignal.
```
 * AdxDi
```
{ {no_input}, 
e -> [Integer: size (2 by default) ]} 
-> ListOfDoubleSignal (dmMinus/trueRange, dmPlus/trueRange).
```
 * AdxDm
```
{ {no_input}, 
e -> [Integer: size (2 by default) ]} 
-> ListOfDoubleSignal (dmMinus, dmPlus).
```
 * AdxDxi
```
{ {no_input}, 
e -> [Integer: N (14 by default), size (2 by default) ]} 
-> DoubleSignal.
```
 * AdxAdxr
```
{ {no_input},
e -> [Integer: N (14 by default) ]}
-> DoubleSignal.
```
##### stsc.algorithms.stock.indices.atr
 * AtrTrueRange
```
{ {no_input}, 
e -> [Integer: size (2 by default) ]}
-> DoubleSignal.
```
 * AtrAtr
```
{ {no_input}, 
e -> [Integer: size (2 by default), N (14 by default) ]}
-> DoubleSignal.
```
##### stsc.algorithms.stock.indices.bb
 * BollingerBands
```
{ {1: DoubleSignal}, 
e -> [Integer: size (2 by default), N (20 by default) ]
e -> [Double: K (2.0 by default) ]}
-> ListOfDoubleSignal.
```
##### stsc.algorithms.stock.indices.ikh
 * IkhChikou
```
{ {no_input}, 
e -> [Integer: size (2 by default), TM (26 by default) ]}
-> DoubleSignal.
```
 * IkhKejun
```
{ {no_input}, 
e -> [Integer: size (2 by default), TM (26 by default) ]}
-> DoubleSignal.
```
 * IkhPrototype
```
{ {no_input}, 
e -> [Integer: size (2 by default), TM (26 by default), TS (9 by default) ]}
-> DoubleSignal.
```
 * IkhSenkauA
```
{ {no_input}, 
e -> [Integer: size (2 by default), TM (26 by default), TS (9 by default) ]}
-> DoubleSignal.
```
 * IkhSenkauB
```
{ {no_input}, 
e -> [Integer: size (2 by default), TM (26 by default), TL (52 by default) ]}
-> DoubleSignal.
```
 * IkhTenkan
```
{ {no_input}, 
e -> [Integer: size (2 by default), TS (9 by default) ]}
-> DoubleSignal.
```
##### stsc.algorithms.stock.indices.macd
 * MacdDivergence
```
{ {1: DoubleSignal},
e -> [Integer: size (2 by default), S (12 by default), L (26 by default) ]}
-> DoubleSignal.
```
 * MacdMacd 
```
{ {1: DoubleSignal},
e -> [Integer: size (2 by default), S (12 by default), L (26 by default) ]}
-> DoubleSignal.
```
 * MacdSignal 
```
{ {1: DoubleSignal},
e -> [Integer: size (2 by default), S (12 by default), L (26 by default), A (9 by default) ]}
-> DoubleSignal.
```
##### stsc.algorithms.stock.indices.mfi
 * MfiMoneyFlow 
```
{ {no_input},
e -> [Integer: size (2 by default) ]}
-> DoubleSignal.
```
 * MfiMfi
```
{ {no_input},
e -> [Integer: N (14 be default), size (2 by default) ]}
-> DoubleSignal.
```
##### stsc.algorithms.stock.indices.msi
 * McClellanOscillator
```
{ {1: DoubleSignal},
e -> [Integer: size (2 by default) ],
e -> [Double: slowP (0.1 by default), fastP (0.05 by default) ]}
-> DoubleSignal.
```
##### stsc.algorithms.stock.indices.rsi
 * RsiD
```
{ {no_input},
e -> [Integer: size (2 by default) ]}
-> DoubleSignal.
```
 * RsiRsi
```
{ {no_input},
e -> [Integer: size (2 by default) ],
e -> [Double: P (0.3 by default) ]}
-> DoubleSignal.
```
 * RsiU
```
{ {no_input},
e -> [Integer: size (2 by default) ]}
-> DoubleSignal.
```
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
