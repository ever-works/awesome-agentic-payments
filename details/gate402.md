# Gate402

## Overview
x402 M2M payment gateway with unified storefront of pay-per-call endpoints.

## Features
- Unified `/v1/*` storefront of 12 pay-per-call endpoints
- Indexed in CDP x402 Bazaar
- Base trading-agent loop
- On-chain wallet/token intel
- DEX price/liquidity + cross-DEX arbitrage
- Market news + sentiment
- SEC EDGAR filings
- Web→Markdown scraping
- Token compression (~40% fewer LLM tokens)
- Semantic vector cache
- Multi-network USDC (Base/Polygon/Arbitrum/Solana)
- Coinbase CDP facilitator
- x402 or non-crypto API-key/Stripe rail
- No signup required
- MCP server: `npx -y gate402-mcp` (15 tools, free-credit tier)

## Pricing
Per-endpoint pricing (e.g., $0.02, $0.03, $0.01, etc.). Free-credit tier for MCP.

## Deployment
Hosted gateway service.

## Integrations
- Discovery: https://gate402.app/.well-known/x402.json
- Catalog: https://gate402.app/v1
- npm: https://www.npmjs.com/package/gate402-mcp
- MCP Registry: https://registry.modelcontextprotocol.io/v0/servers?search=io.github.pgalyen1987
- Website: https://gate402.app
