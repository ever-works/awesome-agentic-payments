## Overview

PayPerByte provides per-byte data feeds and oracles for AI agents via x402 payments.

## Features

- Per-byte data feeds & oracles for AI agents
- Pay-per-call in USDC on Base mainnet over x402
- No API key, no token required
- Subscribe to first-party feeds across markets, weather, threat-intel, and legal
- Decision oracles: address-reputation, sanctions screening
- 15 MCP tools including byte_buy_data
- One-off via gateway at https://x402.payperbyte.io/feeds
- Priced per feed in USDC (flagship $0.05 address-reputation)
- Every paid response emits an EIP-712 PayloadAttestation
- Subscribers re-derive keccak256 over received bytes and recover the signer before trusting
- Fails closed on tamper
- Attestation domain anchored on Arbitrum Sepolia (audit-gated for mainnet)

## Pricing

Per feed in USDC (flagship $0.05 address-reputation).

## Deployment

npm package (MCP server); Smithery and MCP Registry available.