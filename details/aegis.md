## Overview

AEGIS is a network forensics and adversarial verification network for AI agents operating on Base mainnet.

## Features

- `/v2/forensics` endpoint ($0.25) runs six checks: TLS interception, DNS hijack, captive portal manipulation, CT violations via offline SCT verification (no third-party lookup API), NTP drift, and route anomaly
- `/v1/verify` endpoint ($0.50-$4.00) runs a three-critic adversarial chain
- `/v1/synthesize` endpoint ($2.00-$5.00) performs multi-source synthesis
- Self-hosted 35B inference, no third-party model API
- Every result hash anchored on-chain to Base for independent verification
- Settles inline via CDP facilitator, result returned in the same request

## Integrations

- x402 v2 discovery via `.well-known/x402.json`
- OpenAPI spec available
- llms.txt available
- Listed on x402-list.com

## Pricing

- `/v2/forensics`: $0.25 per call
- `/v1/verify`: $0.50-$4.00 per call
- `/v1/synthesize`: $2.00-$5.00 per call
- Settlement: USDC on Base via CDP facilitator