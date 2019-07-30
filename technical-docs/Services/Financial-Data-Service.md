## Financial Data Microservice
---

This microservice is tasked with interfacing with the iex trading api
to obtain investment data on the behalf of client requests

### Features
---
This microservice should obtain and expose endpoints to the following
data points. Any value enclosed in paranthesis portrays the amount of points associated
with each api call to the iex trading exchange. The monthly limit for the free tier is 5,000,000 points.

- Stock Quotes (1)
- Company Info (1)
- 1 Month Historical Prices (10/day)
- Past Year Dividends (10)
- Company News (1 per news returned)
- Cash Flow Statement (1000)
- Advanced Company Stats (3000)
- Balance Sheet (3000)
- Earnings (1000)
- Earnings Today (1000) per symbol + 1 per quote
- Earnings Estimates (10,000)
- Financials (5000)
- Financials As Reported (10-k & 10-Q) (5000)
- Historical Prices (10 per symbol per time interval (1d))
- Income Statement (1000)
- Top 10 insiders (5000)
- Insider Summary (5000)
- Top 10 institutional Owners (10,000)
- IPO Calendar
  - (100 per ipo - upcoming-ipos)
  - (500 per ipo - today-ipos)
- Key Stats (5)
- Largest trades (1 per trade returned)
- Logo (1)
- Market volume (1)
- Options (1000 per symbol)
- Peers (500 per call)
- Price Target (500)
- Recommendations Trend (1000)
- Sector Performance (1 per sector)
- Volumen By Venue (20)
- CEO Compensation (20)
- Crypto (1)
- Social Sentiment (100 per symbol)
