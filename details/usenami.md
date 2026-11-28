## Overview

Usenami is a multi-venue perp funding & RWA spread API for arb-aware AI agents, providing 6 pay-per-call endpoints on Base mainnet.

## Features

- Per-venue funding rates across 30+ exchanges (/v1/funding/current, $0.001)
- Cross-venue funding spread (/v1/perp/funding-spread?ticker=BTC, $0.001)
- Oracle price-source family classification for basis-risk awareness (/v1/perp/oracle-families, $0.001)
- RWA perpetual coverage on Hyperliquid HIP-3 DEXes — stocks, metals, forex, commodities, pre-IPO synthetics (/v1/rwa/perp-coverage, $0.001)
- Historical funding for backtesting (/v1/funding/historical, $0.005, 90d retention)
- Sized-depth quotes with precomputed slippage at $1K/$5K/$10K notional ($0.010)
- x402 v2 with Bazaar discovery extension via Coinbase CDP Facilitator
- MCP server with 6 paid + 2 free tools

## Pricing

- $0.001–$0.010 USDC per call on Base mainnet

## Deployment

Cloud-hosted on Base mainnet via x402 payment rail.