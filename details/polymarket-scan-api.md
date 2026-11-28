## Overview

Polymarket Scan API is an automated market scanner for Polymarket that detects liquidity anomalies and trade opportunities. It scans all active markets every 60 seconds via Cron and provides two paid endpoints.

## Features

- Automated Polymarket market scanner
- Detects liquidity anomalies and trade opportunities
- Scans all active markets every 60s via Cron
- Endpoint: /scan/liquidity-anomaly ($0.018 USDC)
- Endpoint: /scan/history ($0.005 USDC, time-series data up to 24h)
- Cloudflare Workers + Hono
- Open source on GitHub
- Live endpoint available

## Pricing

- /scan/liquidity-anomaly: $0.018 USDC
- /scan/history: $0.005 USDC

## License

Open source (see GitHub)

## Deployment

Cloud-hosted on Cloudflare Workers

## Integrations

- x402 payment protocol
- Base mainnet USDC
- GitHub repository: github.com/TKtokyo/polymarket-scan-api
- Live at polymarket-scan-api.tatsu77.workers.dev