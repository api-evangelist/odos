# Odos (odos)

Odos is a DEX aggregator and smart order routing platform that uses a sophisticated optimization algorithm to unify fragmented liquidity and maximize the output of every trade. The platform scans 1050+ liquidity pools across 15 EVM-compatible chains to find optimal swap routes while accounting for gas costs. Since launching in 2022, Odos has facilitated over $100B in transaction volume and served 3.2M+ unique wallets. Odos provides REST APIs for token swap quotes, optimal routing, slippage management, multi-token transaction execution, token pricing, and liquidity zap operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/odos/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/odos/refs/heads/main/apis.yml)

## Tags

- DEX
- Aggregator
- DeFi
- Token Swaps
- Liquidity
- Routing
- Blockchain
- EVM
- Web3

## Timestamps

- **Created:** 2026-06-14
- **Modified:** 2026-06-14

## APIs

### Odos Smart Order Router API

The Odos Smart Order Router (SOR) API provides REST endpoints for obtaining optimal token swap quotes, assembling swap transaction data, and executing multi-token swaps across 15 EVM-compatible blockchains. The API aggregates liquidity from DEXs, AMMs, on-chain order books, lending protocols, and private RFQ systems to maximize trade output net of gas costs. Supports simple swaps, advanced market orders, limit orders, and cross-chain swaps. SOC 2 Type II compliant.

- **Human URL:** [https://docs.odos.xyz/](https://docs.odos.xyz/)
- **Base URL:** `https://api.odos.xyz`

#### Tags

- DEX Aggregator
- Token Swaps
- Liquidity Routing
- Quote
- Assemble
- Execute

#### Properties

- [Documentation](https://docs.odos.xyz/)
- [OpenAPI](https://api.odos.xyz/sor/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Plans](https://raw.githubusercontent.com/api-evangelist/odos/refs/heads/main/plans/apis.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/odos/refs/heads/main/rate-limits/apis.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/odos/refs/heads/main/finops/apis.yml)

### Odos Token Pricing API

The Odos Token Pricing API provides real-time price data for 100,000+ DeFi assets across 15 supported blockchain networks. The pricing data is DeFi-native and sourced directly from on-chain liquidity, delivering accurate pricing for tokens listed on decentralized exchanges. Available as a standalone service through the QuickNode marketplace or as part of the core Odos API offering.

- **Human URL:** [https://docs.odos.xyz/](https://docs.odos.xyz/)
- **Base URL:** `https://api.odos.xyz`

#### Tags

- Token Pricing
- DeFi
- On-chain Data
- Price Feeds

#### Properties

- [Documentation](https://docs.odos.xyz/)
- [Plans](https://raw.githubusercontent.com/api-evangelist/odos/refs/heads/main/plans/apis.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/odos/refs/heads/main/rate-limits/apis.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/odos/refs/heads/main/finops/apis.yml)

### Odos Liquidity Zaps API

The Odos Liquidity Zaps API enables streamlined single-transaction liquidity provisioning with optimized routing. Users can provide liquidity to DeFi protocols using any token combination in a single transaction, with Odos handling all intermediate swaps and routing automatically to minimize costs and slippage.

- **Human URL:** [https://docs.odos.xyz/](https://docs.odos.xyz/)
- **Base URL:** `https://api.odos.xyz`

#### Tags

- Liquidity
- Zaps
- DeFi
- AMM
- Liquidity Provision

#### Properties

- [Documentation](https://docs.odos.xyz/)
- [Plans](https://raw.githubusercontent.com/api-evangelist/odos/refs/heads/main/plans/apis.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/odos/refs/heads/main/rate-limits/apis.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/odos/refs/heads/main/finops/apis.yml)

## Common Properties

- [Portal](https://enterprise.odos.xyz)
- [Documentation](https://docs.odos.xyz/)
- [About](https://docs.odos.xyz/home/about)
- [F A Q](https://docs.odos.xyz/resources/faq)
- [Plans](https://docs.odos.xyz/build/api_pricing)
- [Status](https://status.odos.xyz)
- [Git Hub](https://github.com/odos-xyz)
- [Discord](https://discord.gg/odos)
- [Twitter](https://x.com/odosprotocol)
- [Telegram](https://t.me/OdosProtocol)
- [Forum](https://forum.odos.xyz)
- [App](https://app.odos.xyz)
- [M C P](https://github.com/odos-xyz/odos-mcp)
- [Terms of Service](https://docs.odos.xyz/resources/terms-of-service)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
