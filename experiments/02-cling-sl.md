# Cling Stop Loss for individual positions that moves with the market when grubbed

All experiments done with a 0.001 BTC trade qty

## BTCUSDT: 2023-04-09 01:00 to 2023-04-20 22:00

Good example of decent moves with returning to the beginning. Market started from 28k-, moved to 31k+ and get back to 28k+ within 10 days.

* Step 50, TP 2, SL 5, POS 1, Cling 0-0:     -16.35 USDT    ->  +31.14 USDT  -44.00 USDT =  -16.50 USDT { +331 / -176 }
* Step 50, TP 2, SL 7, POS 1, Cling 0-0:      -4.35 USDT    ->  +37.06 USDT  -39.20 USDT =   -4.45 USDT { +394 / -112 }
* Step 50, TP 2, SL 8, POS 1, Cling 0-0:     -11.99 USDT    ->  +35.75 USDT  -45.20 USDT =  -11.80 USDT { +380 / -113 }
* Step 50, TP 2, SL 9, POS 1, Cling 0-0:     -11.80 USDT    ->  +35.94 USDT  -45.45 USDT =  -11.61 USDT { +382 / -101 }
* Step 50, TP 2, SL 10, POS 1, Cling 0-0:    -10.42 USDT    ->  +37.17 USDT  -45.50 USDT =  -10.23 USDT { +395 / -91 }
* Step 50, TP 2, SL 20, POS 1, Cling 0-0:     -6.68 USDT    ->  +41.49 USDT  -47.00 USDT =   -6.49 USDT { +441 / -47 }
* Step 50, TP 2, SL 30, POS 1, Cling 0-0:     -5.87 USDT    ->  +43.00 USDT  -48.00 USDT =   -5.68 USDT { +457 / -32 }
* Step 50, TP 2, SL 40, POS 1, Cling 0-0: -13.04 / +137.21 USDT ( -9.50% ) ->  +42.08  -50.00 =   -7.92 { +457 / -25 }
* ➖➖➖
* Step 50, TP 2, SL 10, POS 1, Cling 1-1:      -3.50 USDT    ->  +39.04 USDT  -40.30 USDT =   -3.31 USDT { +415 / -99 }
* Step 50, TP 2, SL 10, POS 1, Cling 2-2:     -10.35 USDT    ->  +37.82 USDT  -45.50 USDT =  -10.16 USDT { +402 / -119 }
* Step 50, TP 2, SL 10, POS 1, Cling 3-3:     -11.88 USDT    ->  +37.73 USDT  -46.85 USDT =  -11.69 USDT { +401 / -123 }
* Step 50, TP 2, SL 10, POS 1, Cling 5-5:      -9.28 USDT    ->  +37.54 USDT  -44.30 USDT =   -9.09 USDT { +399 / -112 }
* ➖➖➖
* Step 50, TP 2, SL 20, POS 1, Cling 2-2:      -8.75 USDT    ->  +42.34 USDT  -49.70 USDT =   -8.56 USDT { +450 / -57 }
* Step 50, TP 2, SL 20, POS 1, Cling 5-5:    -4.11 /  +69.14 USDT ( -5.94% ) ->  +40.35  -41.80 =   -1.45 { +450 / -56 }
* Step 50, TP 2, SL 20, POS 1, Cling 8-8:     -14.33 USDT    ->  +41.49 USDT  -54.20 USDT =  -14.14 USDT { +441 / -68 } 💼  +75.34 USDT ROI -19.02%
* Step 50, TP 2, SL 20, POS 1, Cling 10-10:  -2.43 /  +73.99 USDT ( -3.28% ) ->  +40.70  -42.85 =   -2.15 { +454 / -57 }
* Step 50, TP 2, SL 20, POS 1, Cling 12-12:  -7.14 /  +72.50 USDT ( -9.86% ) ->  +42.62  -48.40 =   -6.95 USDT { +453 / -56 }
* ➖➖➖
* Step 50, TP 2, SL 30, POS 1, Cling 5-5:   -10.00 / +106.77 USDT ( -9.37% ) ->  +43.37  -52.30 =   -9.81 { +461 / -42 }
* Step 50, TP 2, SL 30, POS 1, Cling 10-10: -20.59 / +104.43 USDT ( -19.72% ) ->  +42.61  -55.10 =  -13.49 { +453 / -48 }
* Step 50, TP 2, SL 30, POS 1, Cling 15-15: -24.36 /  +98.59 USDT ( -24.71% ) ->  +40.49  -60.80 =  -20.31 { +449 / -49 }
* Step 50, TP 2, SL 30, POS 1, Cling 20-20:  -8.22 / +102.41 USDT ( -8.03% ) ->  +43.47  -50.70 =   -8.03 { +462 / -38 }
* ➖➖➖
* Step 50, TP 2, SL 40, POS 1, Cling 5-5:   -23.38 / +137.03 USDT ( -17.06% ) ->  +42.52  -52.10 =   -9.58 { +464 / -31 }
* Step 50, TP 2, SL 40, POS 1, Cling 10-10: -27.21 / +134.71 USDT ( -20.20% ) ->  +43.27  -55.45 =  -12.94 { +460 / -36 }
* Step 50, TP 2, SL 40, POS 1, Cling 15-15: -23.31 / +132.52 USDT ( -17.59% ) ->  +42.24  -51.75 =   -9.51 { +461 / -31 }
* Step 50, TP 2, SL 40, POS 1, Cling 20-20: -33.55 / +134.95 USDT ( -24.86% ) ->  +43.18  -62.85 =  -20.46 { +459 / -37 }
* Step 50, TP 2, SL 40, POS 1, Cling 25-25: -24.90 / +135.18 USDT ( -18.42% ) ->  +43.75  -67.65 =  -24.71 { +465 / -38 }

## BTCUSDT: 2023-03-10 09:00 to 2023-03-22 09:00

Example of a huge market move in one direction. Price rises from 19k to 29k over 20 days

* Step 50, TP 2, SL 5, POS 1, Cling 0-0:      -22.91 USDT    ->  +82.61 USDT -112.00 USDT =  -37.30 USDT { +870 / -449 }
* Step 50, TP 2, SL 7, POS 1, Cling 0-0:      -24.04 USDT    ->  +98.94 USDT -117.95 USDT =  -24.98 USDT { +1042 / -337 }
* Step 50, TP 2, SL 8, POS 1, Cling 0-0:   ?    +5.52 USDT    -> +106.92 USDT  -97.60 USDT =   +4.98 USDT { +1126 / -244 }
* Step 50, TP 2, SL 9, POS 1, Cling 0-0:       -4.29 USDT    -> +106.54 USDT -107.10 USDT =   -4.78 USDT { +1122 / -238 }
* Step 50, TP 2, SL 10, POS 1, Cling 0-0:  wrong! +9.49 /  +42.24 USDT ( 22.46% ) -> +109.67  -96.50 =   +9.74 { +1155 / -193 }
* Step 50, TP 2, SL 10, POS 1, Cling 0-0: -10.18 /  +42.46 USDT ( -23.98% ) -> +100.73 -113.50 =  -12.77 { +1133 / -227 }
* Step 50, TP 2, SL 20, POS 1, Cling 0-0: -57.06 /  +70.37 USDT ( -81.09% ) -> +105.20 -161.00 =  -55.80 { +1159 / -161 }
* Step 50, TP 2, SL 30, POS 1, Cling 0-0: -86.27 /  +98.32 USDT ( -87.74% ) -> +109.73 -186.00 =  -76.27 { +1195 / -124 }
* Step 50, TP 2, SL 40, POS 1, Cling 0-0:-146.67 / +126.20 USDT ( -116.23% ) -> +110.67 -234.00 = -123.33 { +1203 / -117 }
* ➖➖➖
* Step 50, TP 2, SL 10, POS 1, Cling 1-1: -22.43 /  +47.20 USDT ( -47.51% ) -> +103.04 -119.90 =  -22.17 { +1085 / -296 }
* Step 50, TP 2, SL 10, POS 1, Cling 2-2: -27.19 /  +42.18 USDT ( -64.47% ) ->  +96.35 -127.40 =  -31.05 { +1119 / -328 }
* Step 50, TP 2, SL 10, POS 1, Cling 3-3:  ?   -12.40 USDT    -> +106.84 USDT -113.60 USDT =  -12.14 USDT { +1125 / -299 }
* Step 50, TP 2, SL 10, POS 1, Cling 5-5:  ?   -24.93 USDT    -> +106.84 USDT -126.05 USDT =  -24.83 USDT { +1125 / -311 }
* ➖➖➖
* Step 50, TP 2, SL 20, POS 1, Cling 2-2:   ?  +47.83 USDT    -> +121.06 USDT  -69.90 USDT =  +49.61 USDT { +1275 / -86 }
* Step 50, TP 2, SL 20, POS 1, Cling 5-5: wrong! +55.09 /  +67.67 USDT ( 81.41% ) -> +121.34  -63.65 =  +55.98 { +1278 / -96 }
* Step 50, TP 2, SL 20, POS 1, Cling 5-5: -27.59 /  +68.54 USDT ( -40.25% ) -> +110.93 -140.75 =  -29.82 { +1226 / -184 }
* Step 50, TP 2, SL 20, POS 1, Cling 8-8:   ?  +51.67 USDT    -> +122.00 USDT  -68.25 USDT =  +51.93 USDT { +1285 / -102 }
* Step 50, TP 2, SL 20, POS 1, Cling 10-10: ?  +45.92 USDT    -> +121.72 USDT  -73.10 USDT =  +46.82 USDT { +1282 / -101 }
* Step 50, TP 2, SL 20, POS 1, Cling 12-12: ?  +25.34 USDT    -> +121.81 USDT  -93.90 USDT =  +25.80 USDT { +1283 / -119 }
* ➖➖➖
* Step 50, TP 2, SL 30, POS 1, Cling 5-5:     -29.28 USDT    -> +118.32 USDT -139.50 USDT =  -23.28 USDT { +1246 / -115 }
* Step 50, TP 2, SL 30, POS 1, Cling 10-10:   -32.24 USDT    -> +118.51 USDT -143.15 USDT =  -27.00 USDT { +1248 / -129 }
* Step 50, TP 2, SL 30, POS 1, Cling 15-15: wrong! +55.51 /  +85.41 USDT ( 64.99% ) -> +124.76  -67.25 =  +56.40 { +1314 / -62 }
* Step 50, TP 2, SL 30, POS 1, Cling 15-15: -57.72 /  +91.93 USDT ( -62.78% ) -> +114.06 -169.05 =  -54.99 { +1247 / -145 }
* Step 50, TP 2, SL 30, POS 1, Cling 20-20:   -29.55 USDT    -> +119.37 USDT -142.25 USDT =  -25.01 USDT { +1257 / -116 }
* ➖➖➖
* Step 50, TP 2, SL 40, POS 1, Cling 5-5:  -109.61 / +124.05 USDT ( -88.36% ) -> +115.23 -210.10 =  -94.87 { +1252 / -121 }
* Step 50, TP 2, SL 40, POS 1, Cling 10-10:-120.33 / +119.50 USDT ( -100.70% ) -> +115.07 -226.65 = -111.58 { +1256 / -138 }
* Step 50, TP 2, SL 40, POS 1, Cling 15-15: -92.87 / +117.46 USDT ( -79.06% ) -> +116.40 -204.95 =  -88.55 { +1268 / -132 }
* Step 50, TP 2, SL 40, POS 1, Cling 20-20: ?  -48.27 USDT    -> +120.70 USDT -162.45 USDT =  -43.74 USDT { +1271 / -107 }
* Step 50, TP 2, SL 40, POS 1, Cling 25-25: ?  -59.79 USDT    -> +120.22 USDT -171.25 USDT =  -53.00 USDT { +1266 / -106 }
* Step 50, TP 2, SL 40, POS 1, Cling 30-30: ?  -66.60 USDT    -> +119.75 USDT -170.70 USDT =  -52.79 USDT { +1261 / -99 }

## BTCUSDT: 2023-03-18 01:00 to 2023-04-09 12:00

Example of long plain market. Price bounced between 26.5k and 29k for over 20 days

* Step 50, TP 2, SL 5, POS 1, Cling 0-0:    -31.44 /  +38.48 USDT ( -81.70% ) ->  +88.02 -110.75 =  -31.38 { +932 / -443 }
* Step 50, TP 2, SL 7, POS 1, Cling 0-0:     -7.51 /  +34.89 USDT ( -21.53% ) ->  +99.54 -101.15 =   -7.27 { +1054 / -289 }
* Step 50, TP 2, SL 8, POS 1, Cling 0-0:    -14.13 /  +37.20 USDT ( -37.99% ) -> +100.01 -108.40 =  -13.69 { +1059 / -271 }
* Step 50, TP 2, SL 9, POS 1, Cling 0-0:     +2.19 /  +40.03 USDT ( 5.48% ) -> +103.60  -96.75 =   +2.63 { +1097 / -215 }
* Step 50, TP 2, SL 10, POS 1, Cling 0-0:  ?  +1.88 /  +42.85 USDT ( 4.38% ) -> +105.96  -99.50 =   +2.57 { +1122 / -199 }
* Step 50, TP 2, SL 20, POS 1, Cling 0-0:  ?   +21.79 USDT    -> +114.35 USDT  -85.00 USDT =  +27.72 USDT { +1211 / -85 }
* Step 50, TP 2, SL 30, POS 1, Cling 0-0:  ?   +60.22 USDT    -> +119.92 USDT  -51.00 USDT =  +68.28 USDT { +1270 / -34 }
* Step 50, TP 2, SL 40, POS 1, Cling 0-0:  ?   +81.14 USDT    -> +121.52 USDT  -24.00 USDT =  +97.30 USDT { +1287 / -12 }
* ➖➖➖
* Step 50, TP 2, SL 10, POS 1, Cling 1-1:    -4.37 /  +43.00 USDT ( -10.17% ) -> +105.11 -103.70 =   -3.68 { +1113 / -260 }
* Step 50, TP 2, SL 10, POS 1, Cling 2-2:    +5.28 /  +42.70 USDT ( 12.37% ) -> +107.00  -96.35 =   +5.72 { +1133 / -252 }
* Step 50, TP 2, SL 10, POS 1, Cling 3-3:    -3.67 /  +43.03 USDT ( -8.53% ) -> +105.20 -102.90 =   -2.98 { +1114 / -270 }
* Step 50, TP 2, SL 10, POS 1, Cling 5-5:   -21.95 /  +42.95 USDT ( -51.11% ) -> +103.78 -119.65 =  -21.71 { +1099 / -299 }
* ➖➖➖
* Step 50, TP 2, SL 20, POS 1, Cling 2-2:   +22.00 /  +71.53 USDT ( 30.75% ) -> +116.15  -88.20 =  +25.83 { +1230 / -109 }
* Step 50, TP 2, SL 20, POS 1, Cling 5-5:    +3.73 /  +68.69 USDT ( 5.43% ) -> +113.88 -105.20 =   +5.92 { +1206 / -143 }
* Step 50, TP 2, SL 20, POS 1, Cling 8-8:   +33.19 /  +70.02 USDT ( 47.40% ) -> +117.57  -81.20 =  +34.17 { +1245 / -111 }
* Step 50, TP 2, SL 20, POS 1, Cling 10-10: +20.82 /  +70.02 USDT ( 29.74% ) -> +116.72  -93.10 =  +21.26 { +1236 / -120 }
* ➖➖➖
* Step 50, TP 2, SL 30, POS 1, Cling 5-5:   +41.43 /  +98.53 USDT ( 42.05% ) -> +119.26  -69.05 =  +49.00 { +1263 / -63 }
* Step 50, TP 2, SL 30, POS 1, Cling 10-10: +39.08 /  +95.32 USDT ( 41.00% ) -> +119.17  -72.00 =  +45.81 { +1262 / -71 }
* Step 50, TP 2, SL 30, POS 1, Cling 15-15: +39.96 /  +92.94 USDT ( 42.99% ) -> +119.64  -70.80 =  +47.53 { +1267 / -68 }
* Step 50, TP 2, SL 30, POS 1, Cling 20-20: +70.09 /  +98.93 USDT ( 70.85% ) -> +121.06  -49.95 =  +70.34 { +1282 / -40 }
* ➖➖➖
* Step 50, TP 2, SL 40, POS 1, Cling 5-5:   +62.42 / +123.02 USDT ( 50.74% ) -> +120.96  -48.55 =  +71.84 { +1281 / -30 }
* Step 50, TP 2, SL 40, POS 1, Cling 10-10: +66.30 / +119.53 USDT ( 55.47% ) -> +121.43  -48.50 =  +72.23 { +1286 / -37 }
* Step 50, TP 2, SL 40, POS 1, Cling 15-15: +68.41 / +123.16 USDT ( 55.55% ) -> +121.43  -46.45 =  +74.33 { +1286 / -34 }
* Step 50, TP 2, SL 40, POS 1, Cling 20-20: +70.68 / +122.51 USDT ( 57.69% ) -> +121.43  -42.55 =  +78.25 { +1286 / -33 }
* Step 50, TP 2, SL 40, POS 1, Cling 25-25: +60.26 / +113.78 USDT ( 52.96% ) -> +121.43  -52.90 =  +67.83 { +1286 / -37 }
