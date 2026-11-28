# aegis-buy

## Overview
Trust-gated x402 buyer client with a local spend policy.

## Features
- Checks service's delivery-verified trust score before paying
- Enforces per-call, per-day and lifetime USD caps
- Allow/deny domains
- All policy checks are local and free
- `procure(need, budget)` picks and pays a service under a hard budget
- Returns Ed25519-signed receipt
- Python and JS implementations
- USDC on Base

## Pricing
Free (all policy checks local and free).

## Deployment
Client-side client, no server deployment required.

## Integrations
- PyPI: https://pypi.org/project/aegis-buy/
- npm: https://www.npmjs.com/package/aegis-buy
- GitHub: https://github.com/Donk338/aegis-buy
