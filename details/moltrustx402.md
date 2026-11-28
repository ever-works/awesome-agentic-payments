# @moltrust/x402

## Overview
Trust score middleware for x402 endpoints.

## Features
- One line: `app.use(requireScore({ minScore: 60 }))`
- Extracts paying wallet from X-Payment header
- Looks up MolTrust trust score
- Blocks agents below threshold with 403 + registration link
- Zero dependencies

## Pricing
Free and open source.

## Deployment
Server-side middleware.

## Integrations
- npm package: `@moltrust/x402`
- GitHub: https://github.com/MoltyCel/moltrust-x402
