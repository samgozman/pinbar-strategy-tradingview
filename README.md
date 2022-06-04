# pinbar-strategy-tradingview

(Pinescript) Pinbar trading strategy for TradingView

![Trade example](assets/wrk_1h.png)

## Explanation

The strategy finds the nearest pinbar pattern and opens a position (long or short). You choose your take profit and stop loss multiplier.

* Take Profit - X times the pinbar size from it's highest point.
* Stop loss - X times the pinbar size from it's lowest point.

![Profits explained](assets/profit_mp.png)

You need to determine the best TP/SL combination on your own for each chart. Start from 1:1 or 2:1. Keep in mind your brocker fee.

### More examples

BIG 1D
![BIG 1D](assets/big_1d.png)

BMY 1H
![BMY 1H](assets/bmy_1h.png)

GILD 1H
![GILD 1H](assets/gild_1h.png)

BTC/USD 5M
![BTC/USD 5M](assets/btcusd_5m.png)
