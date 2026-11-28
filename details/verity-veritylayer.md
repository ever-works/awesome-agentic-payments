## Overview

Verity (VerityLayer) is a fail-closed verify-before-you-act trust gate for AI agents.

## Features

- Returns verdict (supported/unsupported/uncertain) plus calibrated 0–1 confidence and evidence
- Abstains rather than guesses
- Keyless, pay-per-call in USDC on Base (eip155:8453)
- Three tiers:
  - /verify/quick: $0.02 (Haiku pre-filter)
  - /verify: $0.25 (Sonnet, grounded with live citations)
  - /verify/pro: $0.35 (Opus)
- Ships an MCP server (io.github.meloliva14/verity-mcp)

## Pricing

- $0.02–$0.35 USDC per call

## Deployment

Cloud API