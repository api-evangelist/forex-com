# FOREX.com

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
