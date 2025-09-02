##Goal
Track price ranges (CPR) and send alerts when price is inside or near the range.


Day 1 -2

What I Did:

Pull top coins by Marketcap from CoinGecko.

Convert symbols to uppercase + add USDT for Binance.

Save coin info (name, symbol, price, market cap, 24h change) to Airtable.

Loop through each coin, get last 2 daily candles (OHLC) from Binance in order to filter out current day partial candle data.

Update Airtable with previous day’s Open, High, Low, Close.


