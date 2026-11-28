## Overview

Micro Data API Factory — Broker is a wallet-free entry layer that issues API keys with trial credit and meters calls against that credit, handing off to x402 paid URLs or fresh trial keys when depleted.

## Pricing

- Trial credit via POST /keys/create (no signup, no wallet)
- Metered calls via POST /broker/call
- x402-paid production routes on Base USDC

## Features

- Instant API key issuance with trial credit
- Call metering against credit balance
- 402-style handoff to direct x402 paid URL, MCP gateway, or fresh trial key
- Factory primitive: new products added by DB insert, not redeploy
- Currently covers weather v1 (current + forecast)

## Integrations

- USDC on Base for micropayments
- x402 payment enforcement
- MCP gateway