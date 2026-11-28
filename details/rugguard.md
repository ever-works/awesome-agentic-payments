## Overview

RugGuard is a pre-trade rug-check API for AI agents that uses deterministic heuristics to assess token and contract risk on Base and Solana SPL.

## Pricing

- $0.01 quick scan
- $0.05 deep scan with per-heuristic audit trail
- $0.005 explain

## Features

- 14 deterministic heuristics on Base
- 5 deterministic heuristics on Solana SPL
- Owner renounced check
- LP locked check
- Honeypot signatures (buy/sell sim + tax)
- Top10 concentration
- Mint authority check
- Bytecode similarity to known rugs (MinHash on 4-byte shingles)
- Deployer rug history
- Hidden owner detection
- Source verified check
- Weighted risk score 0–100
- Verdict and structured red flags
- rug_probability_30d
- Dual-mode v1/v2 x402 wire format

## Integrations

- USDC on Base for micropayments
- x402 payment enforcement

## Documentation

https://rugguard.redfleet.fr/openapi.json
https://rugguard.redfleet.fr/llms.txt