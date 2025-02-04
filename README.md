# market-review
A simple tool that lets you view historical price, with much friendlier limitations than TradingView.

Known limitations:
< 5 minute timeframe: limited to approximately 8,000 bars (2 months of price).
The higher you go, the more price bars you can see. 8,000 bars is the bare minimum as far as any timeframe is considered.

The chart widget is sourced directly from CityIndex, Forex.COM's sister company.

[I've heard enough. Take me there!](https://trustosas.github.io/market-review/)

## How to get a "Session ID"

 You'll need a browser with extension support. On Android, I'd recommend [Kiwi Browser](https://www.apkmirror.com/apk/geometry-ou/kiwi-browser-fast-quiet/). (It's no longer maintained, though; issues on the topic of alternatives are welcome)

1. Install the [Violentmonkey extension](https://violentmonkey.github.io/get-it/).

2. Install [this script](https://greasyfork.org/en/scripts/525888-extract-session-from-cityindex-iframe).

3. Now, whenever you visit https://www.cityindex.com/en-au/forex-trading/eur-usd/ and wait a bit, the Session ID will be copied to your clipboard.

That's all.