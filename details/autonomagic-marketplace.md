# autonomagic-marketplace

## Overview
Plugin marketplace primitive for x402.

## Features
- Drop a JS file in `endpoints/` to register as paid HTTP endpoint
- ~400ms registration via fs.watch
- No restart, no manifest edits
- Generates Bazaar-shape 402 challenge with EIP-712 extras
- `/.well-known/x402.json` manifest
- Agent-card generation
- OpenAPI spec generation
- Zero runtime dependencies
- Production-extracted from api.autonomagic.org's 22 paid endpoints

## Pricing
Free and open source.

## Deployment
Server-side SDK.

## Integrations
- npm package: `autonomagic-marketplace`
- GitHub: https://github.com/premsreelathasugeendran/autonomagic-marketplace
