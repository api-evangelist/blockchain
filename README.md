# Blockchain.com (blockchain)

Bitcoin block explorer data, network statistics, market data, the Blockchain.com Exchange (REST + WebSocket) trading platform, and the Pay Partner API for crypto purchases.

**APIs.json:** [https://www.blockchain.com/api](https://www.blockchain.com/api)

## Tags

- Cryptocurrency
- Bitcoin
- Blockchain Data
- Exchange
- Market Data
- Trading
- Payments
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Blockchain.com Blockchain Data API

Read-only JSON HTTP API for Bitcoin blockchain data — single block, single transaction, block-by-height, single address, multi-address summary, unspent outputs (UTXOs), latest block, and the simple Query API (difficulty, block count, total supply, ETA, averages).

- **Human URL:** [https://www.blockchain.com/explorer/api/blockchain_api](https://www.blockchain.com/explorer/api/blockchain_api)
- **Base URL:** `https://blockchain.info`

#### Tags

- Cryptocurrency
- Bitcoin
- Blockchain Data
- Explorer

#### Properties

- [Documentation](https://www.blockchain.com/explorer/api/blockchain_api)
- [Documentation](https://www.blockchain.com/explorer/api/q)
- [OpenAPI](openapi/blockchain-data-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blockchain-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchain-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blockchain.com Charts, Stats & Market Data API

Aggregated JSON endpoints for Bitcoin network charts (transactions per second, hash rate, difficulty, miners revenue, mempool, etc.), real-time network statistics, mining pool distribution, the BTC ticker (price by fiat currency) and fiat-to-BTC conversion.

- **Human URL:** [https://www.blockchain.com/explorer/api/charts_api](https://www.blockchain.com/explorer/api/charts_api)
- **Base URL:** `https://api.blockchain.info`

#### Tags

- Cryptocurrency
- Bitcoin
- Market Data
- Statistics
- Charts

#### Properties

- [Documentation](https://www.blockchain.com/explorer/api/charts_api)
- [Documentation](https://www.blockchain.com/explorer/api/exchange_rates_api)
- [OpenAPI](openapi/blockchain-charts-stats-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blockchain-charts-stats.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchain-charts-stats.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blockchain.com Exchange REST API

REST trading API for the Blockchain.com Exchange — public market data (symbols, tickers, L2/L3 order books) and authenticated trading (orders, trades, fills, fees), accounts and payments (balances, deposits, withdrawals, whitelist beneficiaries). Authenticates with an `X-API-Token` header.

- **Human URL:** [https://exchange.blockchain.com/api/](https://exchange.blockchain.com/api/)
- **Base URL:** `https://api.blockchain.com/v3/exchange`

#### Tags

- Cryptocurrency
- Exchange
- Trading
- Market Data

#### Properties

- [Documentation](https://exchange.blockchain.com/api/)
- [Documentation](https://api.blockchain.com/v3/)
- [OpenAPI](openapi/blockchain-exchange-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blockchain-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchain-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blockchain.com WebSocket APIs

Real-time WebSocket APIs covering two distinct surfaces — the Bitcoin / blockchain.info explorer socket (unconfirmed transactions, new blocks, per-address activity) and the Blockchain.com Exchange mercury-gateway socket (heartbeat, ticker, L2/L3 order books, prices, symbols, trades, plus authenticated balances and trading).

- **Human URL:** [https://www.blockchain.com/explorer/api/api_websocket](https://www.blockchain.com/explorer/api/api_websocket)
- **Base URL:** `wss://ws.blockchain.info`

#### Tags

- Cryptocurrency
- Bitcoin
- WebSocket
- Real-Time
- Exchange

#### Properties

- [Documentation](https://www.blockchain.com/explorer/api/api_websocket)
- [Documentation](https://exchange.blockchain.com/api/)
- [AsyncAPI](asyncapi/blockchain-com-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/blockchain-charts-stats.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchain-charts-stats.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/blockchain-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchain-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/blockchain-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchain-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blockchain.com Pay Partner API

Partner API for embedding Blockchain.com crypto purchases. Covers authentication, eligibility (supported currencies / regions), quotes (pricing for crypto transactions), and order state. Rate-limited per partner.

- **Human URL:** [https://docs.blockchain.com/pay/api](https://docs.blockchain.com/pay/api)
- **Base URL:** `https://api.blockchain.com/pay`

#### Tags

- Cryptocurrency
- Payments
- Partner

#### Properties

- [Documentation](https://docs.blockchain.com/pay/api)
- [Postman Collection](collections/blockchain-charts-stats.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchain-charts-stats.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/blockchain-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchain-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/blockchain-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchain-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.blockchain.com/api)
- [GitHub Organization](https://github.com/blockchain)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Terms of Service](https://www.blockchain.com/legal/terms)
- [Plans](plans/blockchain-plans-pricing.yml)
- [Rate Limits](rate-limits/blockchain-rate-limits.yml)
- [Fin Ops](finops/blockchain-finops.yml)
- [Vocabulary](vocabulary/blockchain-vocabulary.yml)
- [Rules](rules/blockchain-rules.yml)
- [Schemas](json-schema/)
- [JSON Structure](json-structure/)
- [JSON-LD](json-ld/) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Examples](examples/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
