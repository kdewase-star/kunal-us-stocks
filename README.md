# Kunal US Stocks

A separate blue-and-white PWA for monitoring US stocks.

## What is included

- US market overview: S&P 500, NASDAQ, Dow Jones
- Watchlist stored locally on the device
- Top gainers / losers
- Stock detail cards
- Installable PWA
- GitHub Actions market-data refresh
- Separate branding from the existing Kunal Stocks app

## Deploy

1. Upload every file/folder in this repository to the root of your new GitHub repository.
2. In GitHub, open **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)`.
5. Save.
6. In **Actions**, run **Update US Market Data** manually once.
7. Open the GitHub Pages site.
8. On Android Chrome, use **Add to Home screen** / **Install app**.

## Notes

The data workflow uses the Yahoo Finance chart endpoint without an API key. Market-data availability and timing can vary. The dashboard is for monitoring and not financial advice.
