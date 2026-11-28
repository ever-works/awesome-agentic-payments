## Overview

krewe is a decentralized AI inference network on Base that uses 2-of-3 byte-equal consensus across 3 independent miner nodes before results settle.

## Features

- /v2/predict endpoint fanned out to 3 independent miner nodes
- 2-of-3 byte-equal consensus required before settlement
- 4 pay-per-call endpoints:
  - text.structure ($0.005): entity/email/date extraction
  - text.embed ($0.01): sentence embeddings
  - web.scrape ($0.02): fetch + clean URL payload
  - text.complete ($0.05): quantized SLM completion via Qwen2.5-0.5B-Instruct
- Settlement via EIP-3009 transferWithAuthorization
- Gas paid by the orchestrator (~$0.001 on Base) and recovered from the payment
- No API keys, no signup
- Live consensus events stream at /v2/live WebSocket

## Pricing

- text.structure: $0.005 per call
- text.embed: $0.01 per call
- web.scrape: $0.02 per call
- text.complete: $0.05 per call

## Deployment

Cloud-hosted on Base mainnet via x402 payment rail. SDK, orchestrator, and miner repositories available on GitHub.