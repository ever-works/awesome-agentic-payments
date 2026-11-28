## Overview

FiatDock is a non-custodial MCP marketplace for AI agents that enables discovery and per-call payment for MCP services in USDC over x402 on Base.

## Features

- Non-custodial: funds settle directly buyer-wallet → seller-wallet
- 1% platform fee as on-chain split (0% for seller's first 30 days)
- FiatDock never holds funds
- 3 tools: search_services, get_service, call_service
- call_service auto-handles 402 → sign → retry flow
- Sellers list free and keep 99%
- Verified sellers pass KYC + MCP-security scan
- Non-custodial USDC↔bank on/off-ramp
- npx fiatdock-mcp

## Pricing

- Free to list for sellers
- 1% platform fee on paid calls (0% for first 30 days for sellers)
- Paid per call in USDC over x402 on Base

## Deployment

Cloud-hosted MCP server; self-hostable via open-source repository.

## Links

- MCP: https://fiatdock.com/mcp
- Marketplace: https://fiatdock.com/mcp-marketplace.html
- Source: https://github.com/fiatdock/fiatdock