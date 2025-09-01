##Goal
Track price ranges (CPR) and send alerts when price is inside or near the range.


Day 1 
What I Did
Pull top coins from CoinGecko.
Convert symbols to uppercase + add USDT for Binance.
Save coin info (name, symbol, price, market cap, 24h change) to Airtable.
Loop through each coin, get last 2 daily candles (OHLC) from Binance.
Update Airtable with previous day’s Open, High, Low, Close.


