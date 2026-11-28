## Overview

Regression Incoming provides model-driven 2026 NFL preseason fantasy football rankings for AI agents via x402 USDC micropayments on Base mainnet.

## Endpoints

- GET /v1/rankings/preseason ($1.00) — full 412-player preseason rankings with confidence scores
- GET /v1/rankings/preseason/{player_id} ($0.10) — single-player projection by player ID
- GET /v1/draft-board/half-ppr ($1.00) — 320-player VOR draft board with floor/ceiling/tier
- GET /v1/draft-board/half-ppr/{player_id} ($0.10) — single-player draft board row
- POST /v1/bundle/purchase ($3.00) — 7-day unlimited-access JWT

## Deployment

Cloud-based on Base mainnet via CDP Facilitator.

## Pricing

USDC on Base. Bazaar discovery extension on all 402 responses. No API keys or signup required.

## Resources

- Discovery: https://api.regressionincoming.fyi/.well-known/x402.json
- Catalog: https://api.regressionincoming.fyi/v1/bazaar