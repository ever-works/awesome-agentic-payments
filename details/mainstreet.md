## Overview

MainStreet is a reputation oracle for onchain AI agents on Base that provides preflight checks before x402 payments.

## Features

- /preflight/{address} returns BLOCK/CAUTION/PROCEED in <100ms
- EIP-712 signatures
- Vet any wallet/token before x402 payments
- Covers Virtuals agents, Clanker tokens, DEX launches (Aerodrome/UniV3/BaseSwap)
- DexScreener trending monitoring
- Sniper detection
- Allowlist + denylist with cluster analysis
- Free reads + paywalled premium audits ($0.25-$25 USDC on Base)
- ERC-8004 registered (agentId 53953)
- MCP server @raskhaaa/mainstreet-oracle

## Pricing

Free reads; premium audits $0.25-$25 USDC on Base.

## Deployment

Web application at avisradar-production.up.railway.app/mainstreet.html

## Repository

https://github.com/philpof102-svg/avisradar

## Agent Card

https://avisradar-production.up.railway.app/.well-known/agent.json

## OpenAPI

https://avisradar-production.up.railway.app/api/agent/openapi.json