## Overview

Fly Labs Agentic Market provides YouTube data APIs for AI agents, paid in USDC on Base.

## Endpoints

- POST /api/agents/transcribe ($0.03) — verbatim transcript, language, time-indexed paragraphs, creator chapters, canonical metadata (captions when available, Whisper fallback otherwise, no LLM rewrites)
- POST /api/agents/engagement ($0.02) — view/like/comment counts, derived ratios, composite engagement score, channel info (subscribers included), full video context (tags, categories, thumbnail, availability, live status)

## Deployment

Cloud-based on Base mainnet via x402 USDC.

## Pricing

Pay-per-call USDC micropayments on Base. Transparent cache on every response (cache.hit, cachedAt, ageSec). No signup required.

## Resources

- OpenAPI 3.1: https://flylabs.fun/api/agents/openapi.json
- Manifest: https://flylabs.fun/api/agents