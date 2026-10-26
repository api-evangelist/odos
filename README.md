# Odos (odos)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
