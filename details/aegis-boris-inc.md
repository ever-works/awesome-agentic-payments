## Overview

Aegis by Boris Inc is a trust registry and payment router for x402 that scores services on measured behaviour.

## Features

- Scores services on measured behaviour rather than self-report
- Liveness checks
- Well-formed 402 challenge validation
- On-wire vs registered price honesty
- Paid-delivery spot checks
- Latency and longevity scoring
- 2,463 indexed services
- 1.47M recorded probes (as of 2026-07-27)
- /route acts on verdicts: resells registry service with trust-ranked failover and auth-then-capture
- Failed delivery is never charged
- Ed25519-signed receipts
- Daily tamper-evident hash-chain over the registry
- Root anchored on-chain to Base
- First /trust call free; /discover and /registry.json free

## Pricing

First /trust call free; /discover and /registry.json free.

## Deployment

Web service at aegis.borisinc.com

## Registry

https://aegis.borisinc.com/registry.json

## x402 Discovery

https://aegis.borisinc.com/.well-known/x402

## Agent Card

https://aegis.borisinc.com/.well-known/agent-card.json

## Pairing

Pairs with aegis-buy (spend-policy buyer client): https://github.com/Donk338/aegis-buy