# meter402

## Overview
Per-second streaming/metered settlement for x402.

## Features
- Turns one-shot 402 calls into pay-as-you-consume billing
- Pay a tick, get the next chunk; stop paying, the gate shuts
- One-line `createMeterRouter` Express adapter
- Framework-free `StreamingMeter` core
- MCP server for agents to open sessions and pay tick-by-tick
- EVM on-chain verifier re-derives settlement totals from token Transfer ledger
- MIT license

## Pricing
Free and open source (MIT).

## Deployment
Server-side library with Express adapter.

## Integrations
- GitHub: https://github.com/Risingtell/meter402
