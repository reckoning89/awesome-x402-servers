# Awesome x402 Servers

Awesome Servers with x402 Payment Protocol Integration

> 📅 Updated for June 2025 release of x402 Whitepaper and Protocol Specs

---

## 📄 What is x402?

x402 is an open payment protocol built on top of HTTP using the long-reserved `402 Payment Required` status code. It enables AI agents, clients, and web services to conduct **autonomous pay-per-use payments** using stablecoins such as USDC on EVM-compatible blockchains.

It allows seamless machine-native transactions:

* No API keys
* No subscriptions
* No accounts
* No chargebacks
* Instant payments

**Read the full [x402 Whitepaper](https://x402.org)**

---

## 📁 Community Servers

* Proxy402 - Monetize any link in seconds. [Website](https://proxy402.com) [Github](https://github.com/Fewsats/proxy402)
* HN Early-Money Pulse API - Curated HN side-hustle + finance + Show HN SaaS signals (24h Algolia window, `early_money_signals` + `opportunity_score`). Direct answer to HN #44051555 Financial Trends Feed. Free 3-pulse preview; full feed $0.02 USDC/req on Base. [Preview](https://remote-signal-api.bloom-basil.workers.dev/v1/hn-early-money/preview) [API](https://remote-signal-api.bloom-basil.workers.dev/x402/v1/hn-early-money)
* Remote Signal API - Curated recruiting + indie-builder signal feed: 50 RemoteOK dev/SaaS jobs + 20 HN Show HN (15min cache). Free preview 5+3/day; full feed $0.02 USDC/req on Base. [API](https://remote-signal-api.bloom-basil.workers.dev/x402/v1/signals) [Docs](https://gist.github.com/reckoning89/d87818b2020bbc27590df1fa0c42f175)
* HN SaaS Teardown Feed - Structured Show HN growth intelligence: pricing model, acquisition channels, stack signals, comment velocity (15 cards, 15min cache). Free 3-card preview; full feed $0.05 USDC/req on Base. [Preview](https://care-entering-call-identifies.trycloudflare.com/x402/v1/teardowns/preview) [API](https://care-entering-call-identifies.trycloudflare.com/x402/v1/teardowns)
* Micro-SaaS Flip Lead Feed - Time-sensitive acquisition listings for scout agents: HN Algolia + Indie Hackers cross-links + Reddit r/SaaS (7-day window, flip_signals + urgency_score). Free 3-lead preview; full feed $0.05 USDC/req on Base. [Preview](https://care-entering-call-identifies.trycloudflare.com/x402/v1/saas-flip-leads/preview) [API](https://care-entering-call-identifies.trycloudflare.com/x402/v1/saas-flip-leads)
* Indie Pricing Intelligence API - Daily scrape + diff of 20 indie SaaS pricing pages (HN Show HN + curated stack): tier adds, price changes, packaging shifts. Free 3-entry preview; full delta feed $0.02 USDC/req on Base. [Preview](https://care-entering-call-identifies.trycloudflare.com/x402/v1/pricing-deltas/preview) [API](https://care-entering-call-identifies.trycloudflare.com/x402/v1/pricing-deltas)
* Surplus Gallery x402 Store - Pre-rendered TaskMarket gallery-grade PNG inventory (Cosmos key-art + Civilization infographics, 2–7 MB, SHA256 verified). Free catalog preview; single PNG download $0.35 USDC/asset on Base. [Preview](https://care-entering-call-identifies.trycloudflare.com/x402/v1/gallery/preview) [API](https://care-entering-call-identifies.trycloudflare.com/x402/v1/gallery/cosmos-v5)

---

## Dashboard

* Base Mainnet Charts by programmer [Dune Analytics](https://dune.com/programmer/x402-base-mainnet)
* x402 @lifewillbeokay [Dune Analytics](https://dune.com/lifewillbeokay/x402)


## Demos / Talks

* x402: Building dynamic tools for AI agents, demos, and use-cases. [Youtube](https://www.youtube.com/watch?v=pL5LxhZ8iCY&t=1744s) 
* x402: Internet Native Payments for Humans and AI Agents. [Youtube](https://www.youtube.com/watch?v=_APaEVnyNWE)

---

## 📅 Supported Schemes

* **exact** (current): Uses EIP-3009 (`transferWithAuthorization`)
* **permit** (experimental): Uses EIP-2612 (`permit`) — enables streaming / usage-based payments via routing contracts.
* Future: Hybrid escrow-based settlement and multicall batching.

---

## 💪 Why x402?

* Built for **agentic commerce**
* Instant micropayments (\$0.001 per request possible)
* Supports AI agents, APIs, content paywalls, cloud compute, etc.
* No subscriptions, no API keys, no manual billing

---

## 🔎 Further Reading

* [x402 Whitepaper (May 2025)](https://x402.org)
* [EIP-3009 Spec](https://eips.ethereum.org/EIPS/eip-3009)
* [Docs](https://x402.gitbook.io/)
---

## 📗 Community

* [Reddit x402](https://www.reddit.com/r/x402)
* [Discord - Coinbase Developer Platform](https://discord.gg/invite/cdp)
* [GitHub - x402](https://github.com/coinbase/x402)
