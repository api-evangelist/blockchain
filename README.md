# Blockchain.com (blockchain)
Bitcoin block explorer data, network statistics, market data, the Blockchain.com Exchange (REST + WebSocket) trading platform, and the Pay Partner API for crypto purchases.

**URL:** [Visit APIs.json URL](https://www.blockchain.com/api)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

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

**Human URL:** [https://www.blockchain.com/explorer/api/blockchain_api](https://www.blockchain.com/explorer/api/blockchain_api)

**Base URL:** `https://blockchain.info`

#### Tags:

 - Cryptocurrency
 - Bitcoin
 - Blockchain Data
 - Explorer

#### Properties

- [Documentation](https://www.blockchain.com/explorer/api/blockchain_api)
- [Simple Query API](https://www.blockchain.com/explorer/api/q)
- [OpenAPI](openapi/blockchain-data-api-openapi.yml)
- [NaftikoCapability](capabilities/data-api-addresses.yaml)
- [NaftikoCapability](capabilities/data-api-blocks.yaml)
- [NaftikoCapability](capabilities/data-api-network.yaml)
- [NaftikoCapability](capabilities/data-api-transactions.yaml)

### Blockchain.com Charts, Stats & Market Data API
Aggregated JSON endpoints for Bitcoin network charts (transactions per second, hash rate, difficulty, miners revenue, mempool, etc.), real-time network statistics, mining pool distribution, the BTC ticker (price by fiat currency) and fiat-to-BTC conversion.

**Human URL:** [https://www.blockchain.com/explorer/api/charts_api](https://www.blockchain.com/explorer/api/charts_api)

**Base URL:** `https://api.blockchain.info`

#### Tags:

 - Cryptocurrency
 - Bitcoin
 - Market Data
 - Statistics
 - Charts

#### Properties

- [Documentation](https://www.blockchain.com/explorer/api/charts_api)
- [Exchange Rates / Ticker](https://www.blockchain.com/explorer/api/exchange_rates_api)
- [OpenAPI](openapi/blockchain-charts-stats-openapi.yml)
- [NaftikoCapability](capabilities/charts-stats-charts.yaml)
- [NaftikoCapability](capabilities/charts-stats-market-data.yaml)
- [NaftikoCapability](capabilities/charts-stats-pools.yaml)
- [NaftikoCapability](capabilities/charts-stats-stats.yaml)

### Blockchain.com Exchange REST API
REST trading API for the Blockchain.com Exchange — public market data (symbols, tickers, L2/L3 order books) and authenticated trading (orders, trades, fills, fees), accounts and payments (balances, deposits, withdrawals, whitelist beneficiaries). Authenticates with an `X-API-Token` header.

**Human URL:** [https://exchange.blockchain.com/api/](https://exchange.blockchain.com/api/)

**Base URL:** `https://api.blockchain.com/v3/exchange`

#### Tags:

 - Cryptocurrency
 - Exchange
 - Trading
 - Market Data

#### Properties

- [Documentation](https://exchange.blockchain.com/api/)
- [REST Reference](https://api.blockchain.com/v3/)
- [OpenAPI](openapi/blockchain-exchange-openapi.yml)
- [NaftikoCapability](capabilities/exchange-market-data.yaml)
- [NaftikoCapability](capabilities/exchange-payments.yaml)
- [NaftikoCapability](capabilities/exchange-trading.yaml)

### Blockchain.com WebSocket APIs
Real-time WebSocket APIs covering two distinct surfaces — the Bitcoin / blockchain.info explorer socket (unconfirmed transactions, new blocks, per-address activity) and the Blockchain.com Exchange mercury-gateway socket (heartbeat, ticker, L2/L3 order books, prices, symbols, trades, plus authenticated balances and trading).

**Human URL:** [https://www.blockchain.com/explorer/api/api_websocket](https://www.blockchain.com/explorer/api/api_websocket)

**Base URL:** `wss://ws.blockchain.info`

#### Tags:

 - Cryptocurrency
 - Bitcoin
 - WebSocket
 - Real-Time
 - Exchange

#### Properties

- [Explorer WebSocket](https://www.blockchain.com/explorer/api/api_websocket)
- [Exchange WebSocket](https://exchange.blockchain.com/api/)
- [AsyncAPI](asyncapi/blockchain-com-asyncapi.yml)

### Blockchain.com Pay Partner API
Partner API for embedding Blockchain.com crypto purchases. Covers authentication, eligibility (supported currencies / regions), quotes (pricing for crypto transactions), and order state. Rate-limited per partner.

**Human URL:** [https://docs.blockchain.com/pay/api](https://docs.blockchain.com/pay/api)

**Base URL:** `https://api.blockchain.com/pay`

#### Tags:

 - Cryptocurrency
 - Payments
 - Partner

#### Properties

- [Documentation](https://docs.blockchain.com/pay/api)

## Common Properties

- [Website](https://www.blockchain.com/api)
- [GitHubOrganization](https://github.com/blockchain)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [TermsOfService](https://www.blockchain.com/legal/terms)
- [Plans](plans/blockchain-plans-pricing.yml)
- [RateLimits](rate-limits/blockchain-rate-limits.yml)
- [FinOps](finops/blockchain-finops.yml)
- [Vocabulary](vocabulary/blockchain-vocabulary.yml)
- [Rules](rules/blockchain-rules.yml)
- [Schemas](json-schema/)
- [JSONStructure](json-structure/)
- [JSONLD](json-ld/)
- [Examples](examples/)

## Features

| Name | Description |
|------|-------------|
| Bitcoin Block Explorer API | Look up any Bitcoin block, transaction, or address via blockchain.info JSON endpoints. |
| Unspent Outputs (UTXOs) | Query unspent outputs for one or more addresses to construct new transactions. |
| Real-Time Streaming | Subscribe to new blocks, unconfirmed transactions, or per-address activity over WebSocket. |
| Charts & Network Statistics | Historical charts and real-time stats for hash rate, difficulty, mempool, miners revenue. |
| Mining Pool Distribution | See which mining pools mined recent blocks via the Pools API. |
| BTC Exchange Rates | Multi-currency ticker plus fiat-to-BTC conversion endpoints. |
| Spot Trading | Place, cancel, and query orders on the Blockchain.com Exchange via REST or WebSocket. |
| Custody & Payments | Deposit, withdraw, and manage whitelisted beneficiaries on the Exchange. |
| Pay Partner Integration | Embed Blockchain.com crypto purchases into partner applications via Pay API. |

## Use Cases

| Name | Description |
|------|-------------|
| Wallet Backends | Build a custodial or non-custodial wallet using address lookups, UTXO queries, and broadcast. |
| Block Explorer | Build a Bitcoin explorer UI on top of the JSON Data API and WebSocket streams. |
| On-Chain Analytics | Aggregate network stats, charts, and pool distribution for research and dashboards. |
| Algorithmic Trading | Run trading strategies against the Exchange REST + WebSocket interfaces. |
| Treasury & Settlement | Programmatically move crypto in and out of custody via the Exchange payments API. |
| Crypto Onboarding | Partner with Blockchain.com Pay to let users buy crypto inside your app. |

## Integrations

| Name | Description |
|------|-------------|
| Bitcoin Core | Blockchain.com surfaces data from Bitcoin Core nodes for explorer endpoints. |
| FIX 4.2 | Exchange WebSocket trading messages use FIX 4.2 field naming. |
| TradingView | Many Exchange clients integrate charts via TradingView using ticker / candle data. |

## Solutions

| Name | Description |
|------|-------------|
| Bitcoin Data Infrastructure | Production-grade read APIs and WebSocket streams for Bitcoin blockchain data. |
| Spot Trading Venue | Institutional and retail spot trading on a global cryptocurrency exchange. |
| Crypto Payments | Embedded crypto purchase rails for fintech and consumer partners. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [blockchain-charts-stats-openapi.yml](openapi/blockchain-charts-stats-openapi.yml)
- [blockchain-data-api-openapi.yml](openapi/blockchain-data-api-openapi.yml)
- [blockchain-exchange-openapi.yml](openapi/blockchain-exchange-openapi.yml)

### AsyncAPI

- [blockchain-com-asyncapi.yml](asyncapi/blockchain-com-asyncapi.yml)

### JSON Schema

- [charts-stats-chart-point-schema.json](json-schema/charts-stats-chart-point-schema.json)
- [charts-stats-chart-schema.json](json-schema/charts-stats-chart-schema.json)
- [charts-stats-pool-distribution-schema.json](json-schema/charts-stats-pool-distribution-schema.json)
- [charts-stats-stats-schema.json](json-schema/charts-stats-stats-schema.json)
- [charts-stats-ticker-entry-schema.json](json-schema/charts-stats-ticker-entry-schema.json)
- [charts-stats-ticker-schema.json](json-schema/charts-stats-ticker-schema.json)
- [com-bitcoin-block-message-payload-schema.json](json-schema/com-bitcoin-block-message-payload-schema.json)
- [com-bitcoin-op-addr-sub-payload-schema.json](json-schema/com-bitcoin-op-addr-sub-payload-schema.json)
- [com-bitcoin-op-addr-unsub-payload-schema.json](json-schema/com-bitcoin-op-addr-unsub-payload-schema.json)
- [com-bitcoin-op-blocks-sub-payload-schema.json](json-schema/com-bitcoin-op-blocks-sub-payload-schema.json)
- [com-bitcoin-op-blocks-unsub-payload-schema.json](json-schema/com-bitcoin-op-blocks-unsub-payload-schema.json)
- [com-bitcoin-op-op-return-sub-payload-schema.json](json-schema/com-bitcoin-op-op-return-sub-payload-schema.json)
- [com-bitcoin-op-ping-block-payload-schema.json](json-schema/com-bitcoin-op-ping-block-payload-schema.json)
- [com-bitcoin-op-ping-payload-schema.json](json-schema/com-bitcoin-op-ping-payload-schema.json)
- [com-bitcoin-op-ping-tx-payload-schema.json](json-schema/com-bitcoin-op-ping-tx-payload-schema.json)
- [com-bitcoin-op-unconfirmed-sub-payload-schema.json](json-schema/com-bitcoin-op-unconfirmed-sub-payload-schema.json)
- [com-bitcoin-op-unconfirmed-unsub-payload-schema.json](json-schema/com-bitcoin-op-unconfirmed-unsub-payload-schema.json)
- [com-bitcoin-utx-message-payload-schema.json](json-schema/com-bitcoin-utx-message-payload-schema.json)
- [com-exchange-admin-event-payload-schema.json](json-schema/com-exchange-admin-event-payload-schema.json)
- [com-exchange-auth-rejected-payload-schema.json](json-schema/com-exchange-auth-rejected-payload-schema.json)
- [com-exchange-auth-subscribe-payload-schema.json](json-schema/com-exchange-auth-subscribe-payload-schema.json)
- [com-exchange-auth-subscribed-payload-schema.json](json-schema/com-exchange-auth-subscribed-payload-schema.json)
- [com-exchange-balances-snapshot-payload-schema.json](json-schema/com-exchange-balances-snapshot-payload-schema.json)
- [com-exchange-cancel-order-request-payload-schema.json](json-schema/com-exchange-cancel-order-request-payload-schema.json)
- [com-exchange-execution-report-payload-schema.json](json-schema/com-exchange-execution-report-payload-schema.json)
- [com-exchange-heartbeat-update-payload-schema.json](json-schema/com-exchange-heartbeat-update-payload-schema.json)
- [com-exchange-l2event-payload-schema.json](json-schema/com-exchange-l2event-payload-schema.json)
- [com-exchange-l3event-payload-schema.json](json-schema/com-exchange-l3event-payload-schema.json)
- [com-exchange-new-order-single-payload-schema.json](json-schema/com-exchange-new-order-single-payload-schema.json)
- [com-exchange-order-mass-cancel-request-payload-schema.json](json-schema/com-exchange-order-mass-cancel-request-payload-schema.json)
- [com-exchange-order-mass-status-request-payload-schema.json](json-schema/com-exchange-order-mass-status-request-payload-schema.json)
- [com-exchange-order-schema.json](json-schema/com-exchange-order-schema.json)
- [com-exchange-prices-update-payload-schema.json](json-schema/com-exchange-prices-update-payload-schema.json)
- [com-exchange-subscribe-action-payload-schema.json](json-schema/com-exchange-subscribe-action-payload-schema.json)
- [com-exchange-subscribe-prices-action-payload-schema.json](json-schema/com-exchange-subscribe-prices-action-payload-schema.json)
- [com-exchange-subscribe-symbol-action-payload-schema.json](json-schema/com-exchange-subscribe-symbol-action-payload-schema.json)
- [com-exchange-symbol-update-payload-schema.json](json-schema/com-exchange-symbol-update-payload-schema.json)
- [com-exchange-symbols-snapshot-payload-schema.json](json-schema/com-exchange-symbols-snapshot-payload-schema.json)
- [com-exchange-ticker-snapshot-payload-schema.json](json-schema/com-exchange-ticker-snapshot-payload-schema.json)
- [com-exchange-trade-update-payload-schema.json](json-schema/com-exchange-trade-update-payload-schema.json)
- [com-exchange-trading-rejected-payload-schema.json](json-schema/com-exchange-trading-rejected-payload-schema.json)
- [com-exchange-trading-snapshot-payload-schema.json](json-schema/com-exchange-trading-snapshot-payload-schema.json)
- [com-exchange-trading-subscribe-payload-schema.json](json-schema/com-exchange-trading-subscribe-payload-schema.json)
- [data-api-address-schema.json](json-schema/data-api-address-schema.json)
- [data-api-block-list-response-schema.json](json-schema/data-api-block-list-response-schema.json)
- [data-api-block-schema.json](json-schema/data-api-block-schema.json)
- [data-api-latest-block-schema.json](json-schema/data-api-latest-block-schema.json)
- [data-api-multi-address-response-schema.json](json-schema/data-api-multi-address-response-schema.json)
- [data-api-transaction-schema.json](json-schema/data-api-transaction-schema.json)
- [data-api-tx-input-schema.json](json-schema/data-api-tx-input-schema.json)
- [data-api-tx-output-schema.json](json-schema/data-api-tx-output-schema.json)
- [data-api-unspent-output-schema.json](json-schema/data-api-unspent-output-schema.json)
- [data-api-unspent-response-schema.json](json-schema/data-api-unspent-response-schema.json)
- [exchange-account-schema.json](json-schema/exchange-account-schema.json)
- [exchange-beneficiary-schema.json](json-schema/exchange-beneficiary-schema.json)
- [exchange-create-order-request-schema.json](json-schema/exchange-create-order-request-schema.json)
- [exchange-create-withdrawal-request-schema.json](json-schema/exchange-create-withdrawal-request-schema.json)
- [exchange-deposit-address-schema.json](json-schema/exchange-deposit-address-schema.json)
- [exchange-deposit-schema.json](json-schema/exchange-deposit-schema.json)
- [exchange-fees-schema.json](json-schema/exchange-fees-schema.json)
- [exchange-fill-schema.json](json-schema/exchange-fill-schema.json)
- [exchange-order-book-schema.json](json-schema/exchange-order-book-schema.json)
- [exchange-order-schema.json](json-schema/exchange-order-schema.json)
- [exchange-price-level-schema.json](json-schema/exchange-price-level-schema.json)
- [exchange-symbol-schema.json](json-schema/exchange-symbol-schema.json)
- [exchange-ticker-schema.json](json-schema/exchange-ticker-schema.json)
- [exchange-trade-schema.json](json-schema/exchange-trade-schema.json)
- [exchange-whitelist-capability-schema.json](json-schema/exchange-whitelist-capability-schema.json)
- [exchange-whitelist-schema.json](json-schema/exchange-whitelist-schema.json)
- [exchange-withdrawal-schema.json](json-schema/exchange-withdrawal-schema.json)

### JSON Structure

- [charts-stats-chart-point-structure.json](json-structure/charts-stats-chart-point-structure.json)
- [charts-stats-chart-structure.json](json-structure/charts-stats-chart-structure.json)
- [charts-stats-pool-distribution-structure.json](json-structure/charts-stats-pool-distribution-structure.json)
- [charts-stats-stats-structure.json](json-structure/charts-stats-stats-structure.json)
- [charts-stats-ticker-entry-structure.json](json-structure/charts-stats-ticker-entry-structure.json)
- [charts-stats-ticker-structure.json](json-structure/charts-stats-ticker-structure.json)
- [com-bitcoin-block-message-payload-structure.json](json-structure/com-bitcoin-block-message-payload-structure.json)
- [com-bitcoin-op-addr-sub-payload-structure.json](json-structure/com-bitcoin-op-addr-sub-payload-structure.json)
- [com-bitcoin-op-addr-unsub-payload-structure.json](json-structure/com-bitcoin-op-addr-unsub-payload-structure.json)
- [com-bitcoin-op-blocks-sub-payload-structure.json](json-structure/com-bitcoin-op-blocks-sub-payload-structure.json)
- [com-bitcoin-op-blocks-unsub-payload-structure.json](json-structure/com-bitcoin-op-blocks-unsub-payload-structure.json)
- [com-bitcoin-op-op-return-sub-payload-structure.json](json-structure/com-bitcoin-op-op-return-sub-payload-structure.json)
- [com-bitcoin-op-ping-block-payload-structure.json](json-structure/com-bitcoin-op-ping-block-payload-structure.json)
- [com-bitcoin-op-ping-payload-structure.json](json-structure/com-bitcoin-op-ping-payload-structure.json)
- [com-bitcoin-op-ping-tx-payload-structure.json](json-structure/com-bitcoin-op-ping-tx-payload-structure.json)
- [com-bitcoin-op-unconfirmed-sub-payload-structure.json](json-structure/com-bitcoin-op-unconfirmed-sub-payload-structure.json)
- [com-bitcoin-op-unconfirmed-unsub-payload-structure.json](json-structure/com-bitcoin-op-unconfirmed-unsub-payload-structure.json)
- [com-bitcoin-utx-message-payload-structure.json](json-structure/com-bitcoin-utx-message-payload-structure.json)
- [com-exchange-admin-event-payload-structure.json](json-structure/com-exchange-admin-event-payload-structure.json)
- [com-exchange-auth-rejected-payload-structure.json](json-structure/com-exchange-auth-rejected-payload-structure.json)
- [com-exchange-auth-subscribe-payload-structure.json](json-structure/com-exchange-auth-subscribe-payload-structure.json)
- [com-exchange-auth-subscribed-payload-structure.json](json-structure/com-exchange-auth-subscribed-payload-structure.json)
- [com-exchange-balances-snapshot-payload-structure.json](json-structure/com-exchange-balances-snapshot-payload-structure.json)
- [com-exchange-cancel-order-request-payload-structure.json](json-structure/com-exchange-cancel-order-request-payload-structure.json)
- [com-exchange-execution-report-payload-structure.json](json-structure/com-exchange-execution-report-payload-structure.json)
- [com-exchange-heartbeat-update-payload-structure.json](json-structure/com-exchange-heartbeat-update-payload-structure.json)
- [com-exchange-l2event-payload-structure.json](json-structure/com-exchange-l2event-payload-structure.json)
- [com-exchange-l3event-payload-structure.json](json-structure/com-exchange-l3event-payload-structure.json)
- [com-exchange-new-order-single-payload-structure.json](json-structure/com-exchange-new-order-single-payload-structure.json)
- [com-exchange-order-mass-cancel-request-payload-structure.json](json-structure/com-exchange-order-mass-cancel-request-payload-structure.json)
- [com-exchange-order-mass-status-request-payload-structure.json](json-structure/com-exchange-order-mass-status-request-payload-structure.json)
- [com-exchange-order-structure.json](json-structure/com-exchange-order-structure.json)
- [com-exchange-prices-update-payload-structure.json](json-structure/com-exchange-prices-update-payload-structure.json)
- [com-exchange-subscribe-action-payload-structure.json](json-structure/com-exchange-subscribe-action-payload-structure.json)
- [com-exchange-subscribe-prices-action-payload-structure.json](json-structure/com-exchange-subscribe-prices-action-payload-structure.json)
- [com-exchange-subscribe-symbol-action-payload-structure.json](json-structure/com-exchange-subscribe-symbol-action-payload-structure.json)
- [com-exchange-symbol-update-payload-structure.json](json-structure/com-exchange-symbol-update-payload-structure.json)
- [com-exchange-symbols-snapshot-payload-structure.json](json-structure/com-exchange-symbols-snapshot-payload-structure.json)
- [com-exchange-ticker-snapshot-payload-structure.json](json-structure/com-exchange-ticker-snapshot-payload-structure.json)
- [com-exchange-trade-update-payload-structure.json](json-structure/com-exchange-trade-update-payload-structure.json)
- [com-exchange-trading-rejected-payload-structure.json](json-structure/com-exchange-trading-rejected-payload-structure.json)
- [com-exchange-trading-snapshot-payload-structure.json](json-structure/com-exchange-trading-snapshot-payload-structure.json)
- [com-exchange-trading-subscribe-payload-structure.json](json-structure/com-exchange-trading-subscribe-payload-structure.json)
- [data-api-address-structure.json](json-structure/data-api-address-structure.json)
- [data-api-block-list-response-structure.json](json-structure/data-api-block-list-response-structure.json)
- [data-api-block-structure.json](json-structure/data-api-block-structure.json)
- [data-api-latest-block-structure.json](json-structure/data-api-latest-block-structure.json)
- [data-api-multi-address-response-structure.json](json-structure/data-api-multi-address-response-structure.json)
- [data-api-transaction-structure.json](json-structure/data-api-transaction-structure.json)
- [data-api-tx-input-structure.json](json-structure/data-api-tx-input-structure.json)
- [data-api-tx-output-structure.json](json-structure/data-api-tx-output-structure.json)
- [data-api-unspent-output-structure.json](json-structure/data-api-unspent-output-structure.json)
- [data-api-unspent-response-structure.json](json-structure/data-api-unspent-response-structure.json)
- [exchange-account-structure.json](json-structure/exchange-account-structure.json)
- [exchange-beneficiary-structure.json](json-structure/exchange-beneficiary-structure.json)
- [exchange-create-order-request-structure.json](json-structure/exchange-create-order-request-structure.json)
- [exchange-create-withdrawal-request-structure.json](json-structure/exchange-create-withdrawal-request-structure.json)
- [exchange-deposit-address-structure.json](json-structure/exchange-deposit-address-structure.json)
- [exchange-deposit-structure.json](json-structure/exchange-deposit-structure.json)
- [exchange-fees-structure.json](json-structure/exchange-fees-structure.json)
- [exchange-fill-structure.json](json-structure/exchange-fill-structure.json)
- [exchange-order-book-structure.json](json-structure/exchange-order-book-structure.json)
- [exchange-order-structure.json](json-structure/exchange-order-structure.json)
- [exchange-price-level-structure.json](json-structure/exchange-price-level-structure.json)
- [exchange-symbol-structure.json](json-structure/exchange-symbol-structure.json)
- [exchange-ticker-structure.json](json-structure/exchange-ticker-structure.json)
- [exchange-trade-structure.json](json-structure/exchange-trade-structure.json)
- [exchange-whitelist-capability-structure.json](json-structure/exchange-whitelist-capability-structure.json)
- [exchange-whitelist-structure.json](json-structure/exchange-whitelist-structure.json)
- [exchange-withdrawal-structure.json](json-structure/exchange-withdrawal-structure.json)

### JSON-LD

- [blockchain-charts-stats-context.jsonld](json-ld/blockchain-charts-stats-context.jsonld)
- [blockchain-com-context.jsonld](json-ld/blockchain-com-context.jsonld)
- [blockchain-data-api-context.jsonld](json-ld/blockchain-data-api-context.jsonld)
- [blockchain-exchange-context.jsonld](json-ld/blockchain-exchange-context.jsonld)

### Examples

- [charts-stats-chart-example.json](examples/charts-stats-chart-example.json)
- [charts-stats-chart-point-example.json](examples/charts-stats-chart-point-example.json)
- [charts-stats-pool-distribution-example.json](examples/charts-stats-pool-distribution-example.json)
- [charts-stats-stats-example.json](examples/charts-stats-stats-example.json)
- [charts-stats-ticker-entry-example.json](examples/charts-stats-ticker-entry-example.json)
- [charts-stats-ticker-example.json](examples/charts-stats-ticker-example.json)
- [com-bitcoin-block-message-payload-example.json](examples/com-bitcoin-block-message-payload-example.json)
- [com-bitcoin-op-addr-sub-payload-example.json](examples/com-bitcoin-op-addr-sub-payload-example.json)
- [com-bitcoin-op-addr-unsub-payload-example.json](examples/com-bitcoin-op-addr-unsub-payload-example.json)
- [com-bitcoin-op-blocks-sub-payload-example.json](examples/com-bitcoin-op-blocks-sub-payload-example.json)
- [com-bitcoin-op-blocks-unsub-payload-example.json](examples/com-bitcoin-op-blocks-unsub-payload-example.json)
- [com-bitcoin-op-op-return-sub-payload-example.json](examples/com-bitcoin-op-op-return-sub-payload-example.json)
- [com-bitcoin-op-ping-block-payload-example.json](examples/com-bitcoin-op-ping-block-payload-example.json)
- [com-bitcoin-op-ping-payload-example.json](examples/com-bitcoin-op-ping-payload-example.json)
- [com-bitcoin-op-ping-tx-payload-example.json](examples/com-bitcoin-op-ping-tx-payload-example.json)
- [com-bitcoin-op-unconfirmed-sub-payload-example.json](examples/com-bitcoin-op-unconfirmed-sub-payload-example.json)
- [com-bitcoin-op-unconfirmed-unsub-payload-example.json](examples/com-bitcoin-op-unconfirmed-unsub-payload-example.json)
- [com-bitcoin-utx-message-payload-example.json](examples/com-bitcoin-utx-message-payload-example.json)
- [com-exchange-admin-event-payload-example.json](examples/com-exchange-admin-event-payload-example.json)
- [com-exchange-auth-rejected-payload-example.json](examples/com-exchange-auth-rejected-payload-example.json)
- [com-exchange-auth-subscribe-payload-example.json](examples/com-exchange-auth-subscribe-payload-example.json)
- [com-exchange-auth-subscribed-payload-example.json](examples/com-exchange-auth-subscribed-payload-example.json)
- [com-exchange-balances-snapshot-payload-example.json](examples/com-exchange-balances-snapshot-payload-example.json)
- [com-exchange-cancel-order-request-payload-example.json](examples/com-exchange-cancel-order-request-payload-example.json)
- [com-exchange-execution-report-payload-example.json](examples/com-exchange-execution-report-payload-example.json)
- [com-exchange-heartbeat-update-payload-example.json](examples/com-exchange-heartbeat-update-payload-example.json)
- [com-exchange-l2event-payload-example.json](examples/com-exchange-l2event-payload-example.json)
- [com-exchange-l3event-payload-example.json](examples/com-exchange-l3event-payload-example.json)
- [com-exchange-new-order-single-payload-example.json](examples/com-exchange-new-order-single-payload-example.json)
- [com-exchange-order-example.json](examples/com-exchange-order-example.json)
- [com-exchange-order-mass-cancel-request-payload-example.json](examples/com-exchange-order-mass-cancel-request-payload-example.json)
- [com-exchange-order-mass-status-request-payload-example.json](examples/com-exchange-order-mass-status-request-payload-example.json)
- [com-exchange-prices-update-payload-example.json](examples/com-exchange-prices-update-payload-example.json)
- [com-exchange-subscribe-action-payload-example.json](examples/com-exchange-subscribe-action-payload-example.json)
- [com-exchange-subscribe-prices-action-payload-example.json](examples/com-exchange-subscribe-prices-action-payload-example.json)
- [com-exchange-subscribe-symbol-action-payload-example.json](examples/com-exchange-subscribe-symbol-action-payload-example.json)
- [com-exchange-symbol-update-payload-example.json](examples/com-exchange-symbol-update-payload-example.json)
- [com-exchange-symbols-snapshot-payload-example.json](examples/com-exchange-symbols-snapshot-payload-example.json)
- [com-exchange-ticker-snapshot-payload-example.json](examples/com-exchange-ticker-snapshot-payload-example.json)
- [com-exchange-trade-update-payload-example.json](examples/com-exchange-trade-update-payload-example.json)
- [com-exchange-trading-rejected-payload-example.json](examples/com-exchange-trading-rejected-payload-example.json)
- [com-exchange-trading-snapshot-payload-example.json](examples/com-exchange-trading-snapshot-payload-example.json)
- [com-exchange-trading-subscribe-payload-example.json](examples/com-exchange-trading-subscribe-payload-example.json)
- [data-api-address-example.json](examples/data-api-address-example.json)
- [data-api-block-example.json](examples/data-api-block-example.json)
- [data-api-block-list-response-example.json](examples/data-api-block-list-response-example.json)
- [data-api-latest-block-example.json](examples/data-api-latest-block-example.json)
- [data-api-multi-address-response-example.json](examples/data-api-multi-address-response-example.json)
- [data-api-transaction-example.json](examples/data-api-transaction-example.json)
- [data-api-tx-input-example.json](examples/data-api-tx-input-example.json)
- [data-api-tx-output-example.json](examples/data-api-tx-output-example.json)
- [data-api-unspent-output-example.json](examples/data-api-unspent-output-example.json)
- [data-api-unspent-response-example.json](examples/data-api-unspent-response-example.json)
- [exchange-account-example.json](examples/exchange-account-example.json)
- [exchange-beneficiary-example.json](examples/exchange-beneficiary-example.json)
- [exchange-create-order-request-example.json](examples/exchange-create-order-request-example.json)
- [exchange-create-withdrawal-request-example.json](examples/exchange-create-withdrawal-request-example.json)
- [exchange-deposit-address-example.json](examples/exchange-deposit-address-example.json)
- [exchange-deposit-example.json](examples/exchange-deposit-example.json)
- [exchange-fees-example.json](examples/exchange-fees-example.json)
- [exchange-fill-example.json](examples/exchange-fill-example.json)
- [exchange-order-book-example.json](examples/exchange-order-book-example.json)
- [exchange-order-example.json](examples/exchange-order-example.json)
- [exchange-price-level-example.json](examples/exchange-price-level-example.json)
- [exchange-symbol-example.json](examples/exchange-symbol-example.json)
- [exchange-ticker-example.json](examples/exchange-ticker-example.json)
- [exchange-trade-example.json](examples/exchange-trade-example.json)
- [exchange-whitelist-capability-example.json](examples/exchange-whitelist-capability-example.json)
- [exchange-whitelist-example.json](examples/exchange-whitelist-example.json)
- [exchange-withdrawal-example.json](examples/exchange-withdrawal-example.json)

## Capabilities

Naftiko capabilities organized as self-contained per-tag definitions (each bundles REST + MCP exposers inline).

| Workflow | Tools | File |
|----------|-------|------|
| Blockchain.com Charts, Stats & Market Data API — Charts | 1 | [capabilities/charts-stats-charts.yaml](capabilities/charts-stats-charts.yaml) |
| Blockchain.com Charts, Stats & Market Data API — Market Data | 2 | [capabilities/charts-stats-market-data.yaml](capabilities/charts-stats-market-data.yaml) |
| Blockchain.com Charts, Stats & Market Data API — Pools | 1 | [capabilities/charts-stats-pools.yaml](capabilities/charts-stats-pools.yaml) |
| Blockchain.com Charts, Stats & Market Data API — Stats | 1 | [capabilities/charts-stats-stats.yaml](capabilities/charts-stats-stats.yaml) |
| Blockchain.com Blockchain Data API — Addresses | 3 | [capabilities/data-api-addresses.yaml](capabilities/data-api-addresses.yaml) |
| Blockchain.com Blockchain Data API — Blocks | 3 | [capabilities/data-api-blocks.yaml](capabilities/data-api-blocks.yaml) |
| Blockchain.com Blockchain Data API — Network | 13 | [capabilities/data-api-network.yaml](capabilities/data-api-network.yaml) |
| Blockchain.com Blockchain Data API — Transactions | 1 | [capabilities/data-api-transactions.yaml](capabilities/data-api-transactions.yaml) |
| Blockchain.com Exchange REST API — Market Data | 6 | [capabilities/exchange-market-data.yaml](capabilities/exchange-market-data.yaml) |
| Blockchain.com Exchange REST API — Payments | 10 | [capabilities/exchange-payments.yaml](capabilities/exchange-payments.yaml) |
| Blockchain.com Exchange REST API — Trading | 8 | [capabilities/exchange-trading.yaml](capabilities/exchange-trading.yaml) |

## Vocabulary

- [Blockchain.com Vocabulary](vocabulary/blockchain-vocabulary.yml) — 10 resources, 5 actions, 11 workflows, 4 personas.

## Rules

- [blockchain-rules.yml](rules/blockchain-rules.yml) — 31 Spectral rules enforcing Blockchain.com API conventions.

## Plans / Pricing

API Commons Plans description of the commercial offering.

- [blockchain-plans-pricing.yml](plans/blockchain-plans-pricing.yml)

## Rate Limits

API Commons Rate Limits description of throttling policies.

- [blockchain-rate-limits.yml](rate-limits/blockchain-rate-limits.yml)

## FinOps

FOCUS-aligned FinOps view of the billable surface.

- [blockchain-finops.yml](finops/blockchain-finops.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

