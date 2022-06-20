# RobustTradingSimulator
## RobustTradingSimulator is a Stock/Crypto trading simulator for manually testing trading strategies and analysing results.
The application allows stepping through a market at any speed allowing trades to be simulated across many years of data very quickly.
It currently has 20 markets each with around 3 years of data from FXCM built in, hence the large size of the download.

# Installation
1. Download latest version from:
https://github.com/Hallupa/RobustTradingSimulator/releases

2. Run 'TradingSimulatorInstaller.msi' which will install the application along with shortcuts on the desktop and start menu

# How to use
After starting the application there will be a random chart from one of 20 markets at a random point in time.

The chart on the left shows day candles, on the right are 2 hour or 4 hour candles.
Clicking 'next candle' or pressing Control-F will progress one candle forward.
Clicking 'New chart' will select another random market and time.

## Setting up a trade
Clicking 'long trade' or 'short trade' will add a new trade in the trades window.
Every trade has to have a stop so the trade can calculate a risk to reward ratio.

### Set stop
Select the new trade, click 'Set stop' then click a point on the chart for the stop.
### Set limit (optional)
If wanted, click 'Set limit' and click a point on the chart for the limit.
### Market price
If no order price has been set, when time is progressed the trade will automatically start at market price.
### Entry price
To set the entry price, click 'Set entry price' then select a point on the chart.
When progressing through the candles, if the entry price is hit the trade will start.

## Editing the trade
When a trade is active selecting the trade then clicking the toolbar option 'Set stop', 'Set limit' or 'Set stop' will then allow selecting a point on the chart.

## Results
In the Results section analysis is shown of the trades, such as average return in in risk to reward ratios, or R, and shows statistics such as % trades that made a positve R, expectancy, etc.

# License

This library is release under GNU General Public License v3.0.

Copyright (c) 2019 Oliver Wickenden

https://github.com/Hallupa/TraderSimulator/blob/master/LICENSE
