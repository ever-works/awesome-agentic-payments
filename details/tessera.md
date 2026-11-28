## Overview

Tessera is a credit identity layer for AI agents on Base, providing a deterministic Tessera Score (0–100) computed from on-chain activity via a published formula.

## Features

- Public deterministic Tessera Score (0–100)
- Computed from on-chain activity via published formula
- No ML, no proprietary model; anyone can reproduce
- Paid x402 endpoints:
  - GET /api/x402/score/[address] ($0.001 USDC): score + tier + percentile + credit-line estimate + five-input breakdown
  - GET /api/x402/agent/[address] ($0.002 USDC): combined Score + verified Agent Directory profile
- Free SDK variants available
- Settlement via Coinbase facilitator on Base mainnet, EIP-3009 transferWithAuthorization

## Pricing

- $0.001 per score lookup
- $0.002 per agent lookup
- Free SDK variants available