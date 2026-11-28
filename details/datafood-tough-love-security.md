## Overview

DataFood provides a universal data hub for AI agents with 17 cross-niche sources behind one POST /api/data/bundle call.

## Sources

- Crypto prices
- ETH gas
- Weather
- News
- HN (Hacker News)
- GitHub trending
- DeFi yield
- Token risk via GoPlus
- HHS healthcare-breach feed
- Geocoding

## Deployment

Cloud-based.

## Pricing

Bundle micropayments save up to 92% vs per-API alternatives. Day pass $0.99 unlimited 24h, week pass $4.99. Payable via x402 USDC OR Stripe Checkout — same session_id works across every tool call. Free 1-row preview at /api/data/preview?type=…&q=….

## Resources

- Live demo: https://toughlovesec.win/agent-mesh
- MCP server: https://github.com/atmflow55/datafood-mcp
- x402 descriptor: https://toughlovesec.win/.well-known/x402.json
- Catalog: https://toughlovesec.win/api/v1/catalog