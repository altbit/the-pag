# Fixed Stop Loss for individual positions

All experiments done with a 0.001 BTC trade qty

## BTCUSDT: 2023-04-09 01:00 to 2023-04-20 22:00

Good example of decent moves with returning to the beginning. Market started from 28k-, moved to 31k+ and get back to 28k+ within 10 days.

### 900 Grid Spread

Market spills 3x+ over the spread, means lots of stop losses. But each SL is not huge

* Classic Bybit Futures grid: exits at 31100 with -153 USDT loss (Max POS 1 analogue)
* ➖➖➖
* Step 30, TP 3, SL 30, Max POS 3:      +2.04 USDT    -> +133.01 USDT -126.90 USDT =   +3.16 USDT { +1582 / -141 }
* Step 30, TP 3, SL 30, Max POS 5:      -1.99 USDT    -> +151.34 USDT -148.50 USDT =   -0.62 USDT { +1800 / -165 }
* Step 30, TP 3, SL 30, Max POS 2:      +4.61 USDT    -> +109.56 USDT -101.70 USDT =   +5.49 USDT { +1303 / -113 }
* Step 30, TP 3, SL 30, Max POS 1:      +5.80 USDT    ->  +70.97 USDT  -63.00 USDT =   +6.50 USDT { +844 / -70 }
* Step 30, TP 3, SL 30, Max POS 1, QTY x10: +57.99 USDT    -> +709.66 USDT -630.00 USDT =  +65.02 USDT { +844 / -70 }
* Step 30, TP 1, SL 30, Max POS 1:     -85.36 USDT    ->  +48.27 USDT  -72.90 USDT =  -26.33 USDT { +2005 / -81 }
* Step 30, TP 5, SL 30, Max POS 1:      -4.68 USDT    ->  +75.22 USDT  -78.30 USDT =   -4.91 USDT { +522 / -87 }
* Step 30, TP 5, SL 30, Max POS 3:      -6.57 USDT    -> +168.44 USDT -171.90 USDT =   -7.47 USDT { +1169 / -191 }
* Step 30, TP 5, SL 30, Max POS 5:      -4.80 USDT    -> +214.98 USDT -216.00 USDT =   -6.06 USDT { +1492 / -240 }
* Step 50, TP 3, SL 30, Max POS 2:      -1.02 USDT    ->  +73.20 USDT  -73.50 USDT =   -1.34 USDT { +508 / -49 }
* ➖➖➖
* Step 50, TP 2, SL 10, Max POS 1:     -10.42 USDT    ->  +37.17 USDT  -45.50 USDT =  -10.23 USDT { +395 / -91 }
* Step 50, TP 2, SL 20, Max POS 1:      -6.68 USDT    ->  +41.49 USDT  -47.00 USDT =   -6.49 USDT { +441 / -47 }
* Step 50, TP 2, SL 30, Max POS 1:      -5.87 USDT    ->  +43.00 USDT  -48.00 USDT =   -5.68 USDT { +457 / -32 }
* Step 50, TP 2, SL 40, Max POS 1:      -6.97 USDT    ->  +43.75 USDT  -50.00 USDT =   -6.78 USDT { +465 / -25 }

### 2100 Grid Spread

Market spills +50%, but as far as SL are bugger the total loss is even bigger and no additional profit

* Step 30, TP 3, SL 70, Max POS 3:      -7.35 USDT    -> +140.25 USDT -144.90 USDT =   -6.12 USDT { +1668 / -69 }
* Step 30, TP 3, SL 70, Max POS 1:     -10.72 USDT    ->  +72.99 USDT  -81.90 USDT =   -9.75 USDT { +868 / -39 }

## BTCUSDT: 2023-03-10 09:00 to 2023-03-22 09:00

Example of a huge market move in one direction. Price rises from 19k to 29k over 20 days

* Step 30, TP 3, SL 30, Max POS 1:    -143.30 USDT    -> +182.79 USDT -316.80 USDT = -140.18 USDT { +2152 / -352 }
* Step 30, TP 3, SL 30, Max POS 2:    -226.94 USDT    -> +285.23 USDT -496.80 USDT = -221.26 USDT { +3358 / -552 }
* Step 30, TP 3, SL 30, Max POS 3:    -268.14 USDT    -> +344.77 USDT -594.00 USDT = -260.81 USDT { +4059 / -660 }
* Step 30, TP 3, SL 70, Max POS 1:    -347.17 USDT    -> +192.05 USDT -489.30 USDT = -301.35 USDT { +2261 / -233 }
* Step 30, TP 3, SL 150, Max POS 1:   -743.78 USDT    -> +195.89 USDT -661.50 USDT = -468.31 USDT { +2306 / -147 }
* Step 50, TP 2, SL 30, Max POS 2:     -78.25 USDT    -> +162.20 USDT -220.50 USDT =  -61.01 USDT { +1708 / -147 }
* Step 50, TP 2, SL 30, Max POS 3:     -91.80 USDT    -> +182.04 USDT -250.50 USDT =  -71.54 USDT { +1917 / -167 }
* Step 50, TP 3, SL 30, Max POS 2:     -86.19 USDT    -> +185.56 USDT -249.00 USDT =  -66.50 USDT { +1280 / -166 }
* Step 70, TP 2, SL 20, Max POS 1:     -28.85 USDT    ->  +87.06 USDT -107.80 USDT =  -22.16 USDT { +645 / -77 }
* ➖➖➖
* Step 50, TP 2, SL 10, Max POS 1:      +9.49 USDT    -> +109.67 USDT  -96.50 USDT =   +9.74 USDT { +1155 / -193 }
* Step 50, TP 2, SL 20, Max POS 1:     -33.61 USDT    -> +111.22 USDT -139.00 USDT =  -30.33 USDT { +1171 / -139 }
* Step 50, TP 2, SL 30, Max POS 1:     -54.84 USDT    -> +114.63 USDT -156.00 USDT =  -43.29 USDT { +1207 / -104 }
* Step 50, TP 2, SL 40, Max POS 1:     -80.36 USDT    -> +116.06 USDT -170.00 USDT =  -55.53 USDT { +1222 / -85 }

## BTCUSDT: 2023-03-18 01:00 to 2023-04-09 12:00

Example of long plain market. Price bounced between 26.5k and 29k for over 20 days

* Step 50, TP 3, SL 30, Max POS 2:     +90.05 USDT    -> +201.06 USDT -103.50 USDT =  +96.18 USDT { +1392 / -69 }
* ➖➖➖
* Step 50, TP 2, SL 10, Max POS 1:  +1.88 /  +42.85 USDT ( 4.38% ) -> +105.96  -99.50 =   +2.57 { +1122 / -199 }
* Step 50, TP 2, SL 20, Max POS 1:     +21.79 USDT    -> +114.35 USDT  -85.00 USDT =  +27.72 USDT { +1211 / -85 }
* Step 50, TP 2, SL 30, Max POS 1:     +60.22 USDT    -> +119.92 USDT  -51.00 USDT =  +68.28 USDT { +1270 / -34 }
* Step 50, TP 2, SL 40, Max POS 1:     +81.14 USDT    -> +121.52 USDT  -24.00 USDT =  +97.30 USDT { +1287 / -12 }
