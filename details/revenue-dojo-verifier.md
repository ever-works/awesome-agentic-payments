## Overview

Revenue Dojo Verifier provides agent payment receipt and mandate verification with a 22-check fail-closed matrix.

## Features

- Settlement predicate (payer≠payee sybil defense)
- Binding resource (receipt bound to specific endpoint)
- Delivery truth (request/response hash binding)
- Identity anchor (payer wallet signature matching)
- Replay protection
- 10 paid routes on Base mainnet via CDP facilitator

## Paid Routes

- /receipt/verify ($0.05)
- /mandate/verify ($0.25)
- /audit/x402 ($1.00)
- /mcp/call ($0.05)
- Plus price/portfolio/opportunities/briefing/research feeds

## Integrations

- OpenAPI 3.0.3 spec: https://x402.167-172-95-184.nip.io/openapi.json
- llms.txt: https://x402.167-172-95-184.nip.io/llms.txt
- Discovery: https://x402.167-172-95-184.nip.io/.well-known/x402
- Offers: https://x402.167-172-95-184.nip.io/offers

## Pricing

Pay-per-call via x402 on Base mainnet. Routes range from $0.05 to $1.00.