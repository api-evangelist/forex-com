# FOREX.com

FOREX.com is a regulated forex and CFD trading broker (a brand of StoneX Group) offering REST and FIX APIs for automated trading and real-time market data access. The REST API is hosted at `ciapi.cityindex.com/TradingAPI` and enables algorithmic traders to authenticate sessions, receive live streaming prices via Lightstreamer, execute buy/sell orders across 80+ forex and CFD markets, and programmatically manage account balances, positions, and order history. A FIX API is available for institutional clients requiring lower-latency direct market connectivity with local liquidity sourcing in London, Tokyo, and New York.

## APIs

- **Session API** — Authenticate and create API sessions using username, password, and AppKey credentials
- **Account API** — Retrieve client account details, trading account IDs, balance, and margin
- **Market API** — Search and resolve Market IDs for 80+ tradeable forex and CFD instruments
- **Pricing API** — Real-time Lightstreamer streaming prices and historical OHLC data (up to 4,000 records per request)
- **Order API** — Place market orders with direction, quantity, stop-loss, take-profit, and price tolerance
- **Position API** — List and monitor open trading positions

## Getting Started

API access requires an active FOREX.com trading account and an AppKey. To obtain an AppKey, contact FOREX.com support at support.en@forex.com — activation typically takes 3 business days.

## Pricing

There is no separate API subscription fee. Trading costs arise through:

- **Spread-Only Account**: Commission-free; costs embedded in bid/ask spread (avg 1.00 pip EUR/USD)
- **RAW Pricing Account**: Tight spreads from 0.2 pips on EUR/USD plus $7 USD commission per $100,000 USD notional traded
- **FIX API (Institutional)**: Pricing negotiated directly with FOREX.com institutional sales

Minimum deposit: $100 (FOREX.com recommends $2,500 for adequate risk management).

## Links

- Website: https://www.forex.com/
- API Trading: https://www.forex.com/en/trading-tools/api-trading/
- Open Account: https://www.forex.com/en-us/trading-accounts/new-trading-account/
- Support: support.en@forex.com
- Python SDK: https://github.com/ali-zahedi/forexcom
