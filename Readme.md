# The Perpetual (future contracts) Advanced Grid bot (🐶 The PAG 🐶)

## Experiments

* [Fixed Stop Loss](./experiments/01-fixed-sl.md)
* [Cling Stop Loss](./experiments/02-cling-sl.md)
* [Airdrop feature](./experiments/03-airdrop.md)
* [Live market grid 70](./experiments/04-live-70.md)


Todo:
1. ✅ Implement constant spread trading bot (Like a classic ByBit Futures grid bot but moving with a market)
2. ✅ Convert all TP/SL orders from Market to Limit (to reduce fees from 0.06% to 0.01%)
3. ✅ Close open conditional orders out of scan spread (to maintain max limit of 10 open orders)
4. ✅ Introduce working spread (Cling SLs). When SL enters the working spread move it with the spread to reduce big losses. Basically the idea is to close SL orders when market bounce back after huge move
5. ✅ Overcome the system limit of 20 take profit and stop loss orders - single Emergency TP and SL for the whole position
6. ✅ Implement floating position trading bot (increasing or decreasing the position based on the strategy and market conditions)
7. ✅ Implement the Market simulation - The Matrix has you!
8. ✅ Track real trading balance - understand the total spent and gain amounts
9. ✅ Introduce Airdrop Mode - huge market moves in a short period
10. ✅ Introduce drops - conditional position decrease/drop in airdrop mode to reduce losses on huge moves
