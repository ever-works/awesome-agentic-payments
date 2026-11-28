# @larkinsh/x402

## Overview
Authorization middleware for x402 endpoints.

## Features
- One line: `preflight(handler, { minScore: 40 })`
- Gates by 5-dimension trust score
- Trust dimensions: wallet age, tx history, counterparties, funding source, ERC-8004
- Returns Ed25519-signed receipts verifiable with public key only
- Supports block / warn / surcharge modes
- Hono / Express / Next adapters

## Pricing
Free and open source.

## Deployment
Server-side middleware.

## Integrations
- npm package: `@larkinsh/x402`
- GitHub: https://github.com/larkin-dev/larkin
