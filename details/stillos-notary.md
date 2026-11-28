## Overview

StillOS Notary provides signed, fail-closed trust & verification primitives for agent-to-agent commerce via x402 USDC on Base.

## Features

- agent-clearance — counterparty credit-check: OFAC SDN + live on-chain wallet screen → CLEAR/REVIEW/BLOCK
- claim-verdict — grade any claim vs external ground truth
- grade-strategy — REAL_EDGE/REGIME_LUCK/NEGATIVE_EV
- screen-entity — OFAC SDN
- insider-conviction/smart-money — proprietary EDGAR scoring
- distress-score — single-ticker distress vs a backtested modified-Altman-Z model

## Deployment

Cloud-based on Base mainnet via self-hosted facilitator (no CDP dependency).

## Pricing

Free tiers, then $0.02–$0.75 x402 USDC on Base. Every response Ed25519-signed and independently verifiable. No account required.

## Resources

- llms.txt: https://nolawealthfinancial.com/llms.txt
- agent.json: https://nolawealthfinancial.com/.well-known/agent.json
- OpenAPI: https://nolawealthfinancial.com/openapi.json
- MCP Registry: https://registry.modelcontextprotocol.io/v0/servers?search=stillos-edge-gate