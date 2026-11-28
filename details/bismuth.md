## Overview

Bismuth is a utility API suite for AI agents on x402, providing 7 pay-per-call services on Base mainnet with no API keys or signup required.

## Services

- **Bismuth Scraping** - $0.02 scrape / $0.10 BFS crawl — Playwright, SSRF-protected
- **Bismuth Screenshot** - $0.01, Playwright PNG/JPEG
- **Bismuth PDF Extraction** - $0.01, OCR + vision mode
- **Bismuth Email** - $0.01, Resend + CC/BCC/attachments
- **Bismuth Search** - $0.01, Tavily-ranked
- **Bismuth Conversion** - $0.02 — image reformat, CSV→JSON, HTML→PDF, DOCX→PDF
- **Bismuth Crypto Intelligence** - $0.01–$0.10, CoinGecko/DeFiLlama/CoinTelegraph/GitHub across 17 major coins

## Deployment

Cloud-based on Base mainnet via x402.

## Pricing

Pay-per-call USDC micropayments on Base mainnet. MCP server available as npm package `x402-mcp-server`.

## Discovery Endpoints

- Scraping: https://x402-scraping-api-production.up.railway.app/.well-known/x402
- Screenshot: https://usdc-screenshot-api-production.up.railway.app/.well-known/x402
- PDF: https://pdf-api-production-cf1e.up.railway.app/.well-known/x402
- Email: https://x402-email-api-production.up.railway.app/.well-known/x402
- Search: https://x402-search-api-production.up.railway.app/.well-known/x402
- Conversion: https://x402-conversion-api-production.up.railway.app/.well-known/x402
- Crypto: https://crypto-sentiment-api-production-0ff4.up.railway.app/.well-known/x402