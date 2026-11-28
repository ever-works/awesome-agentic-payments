## Overview

x402 inference gateway provides OpenAI-compatible LLM chat completions for AI agents, paid per request in USDC on Base mainnet via the Coinbase CDP facilitator.

## Features

- OpenAI-compatible LLM chat completions
- x402 v2 upto scheme: authorize a ceiling derived from max_tokens
- Billed actual token usage at upstream cost + 4%
- From $0.001/call
- 8 models: gpt-5.4-nano/mini, gpt-5.4, gpt-5.5, gpt-4o and gpt-4.1 families
- No API key, no signup
- Billing transparency headers: X-Billed-Usd, X-Quoted-Ceiling-Usd
- Daily on-chain canary
- Self-serve integration doc at GET /
- Bazaar-indexed

## Pricing

- From $0.001/call (upstream cost + 4%)

## Deployment

Cloud-hosted on Railway, settlement via Base mainnet x402 payment rail.