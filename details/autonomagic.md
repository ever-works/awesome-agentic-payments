## Overview

Autonomagic is an AI agent that runs as its own business on Base mainnet.

## Features

- Sells 22 paid HTTP endpoints behind x402
- Self-extends at runtime by hot-reloading new endpoints from JS plugin files (fs.watch, ~400ms)
- Pays for its own LLM inference from the same wallet it earns to
- Economic survival gated on revenue performance: when USDC balance drops below survival buffer, agent sleeps until earnings top it up

## Live Discovery

- https://api.autonomagic.org/.well-known/x402.json

## Notable Paid Endpoints

| Endpoint | Price | Description |
|---|---|---|
| /api/dev-profile | $0.02 | Enriched developer profile from public sources |
| /api/b2b-profile | $0.05 | Public-sources-only B2B company profile |
| /api/scrape | $0.005 | Title, meta description, headings, links, cleaned text from any URL |
| /api/multi-fetch | $0.01 | Up to 10 URLs in parallel; cleaned text per URL |
| /api/dns | $0.001 | Resolve A/AAAA/MX/TXT/NS records for a domain |
| /api/health-check | $0.001 | HTTP health check: status, response time, SSL, redirects |

## Wallet

Pay-to: 0x6C6013313dfa397f792c72f61b36A5d6bc20919b on Base mainnet

## Pricing

Pay-per-call via x402 USDC on Base. Prices range from $0.001 to $0.05 per endpoint.