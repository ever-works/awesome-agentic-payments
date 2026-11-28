## Overview

Kerne Protocol provides proof-of-reserves and signed ERC-20 reads for AI agents.

## Features

- GET /reserves ($0.25): hourly EOA-signed proof-of-reserves attestation for kUSD synthetic dollar (PSM backing ratio, aggregate USD solvency, bound to EIP-191 signature)
- POST /instant-read ($29): EIP-191 signed factual read of any ERC-20
- USDC on Base via Coinbase CDP facilitator
- x402 v2 with Bazaar discovery on every 402
- Same signed reserves blob served free to humans at https://kerne.fi/api/por/signed
- Every response independently verifiable (EIP-191)

## Pricing

- $0.25 per reserves call
- $29 per instant-read call

## Deployment

Cloud API