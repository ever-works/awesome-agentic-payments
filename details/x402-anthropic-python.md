## Overview

x402-anthropic-python is a drop-in Anthropic Python SDK wrapper that transparently handles HTTP 402 x402 payment retry. It wraps httpx transport so anthropic.Anthropic / AsyncAnthropic auto-pays with USDC on EVM (Base, Ethereum) or SVM (Solana) and retries — no call-site changes needed.

## Key Features

- Drop-in Anthropic Python SDK wrapper
- Transparent HTTP 402 x402 payment retry
- Wraps httpx transport
- Auto-pays with USDC on EVM (Base, Ethereum) or SVM (Solana)
- No call-site changes needed

## Deployment

Self-hostable from GitHub repository.

## License

Open source.