## Overview

PaladinFi provides pre-trade trust verification and swap router services for AI agents on Base (8453).

## Features

- Pre-trade trust verification via POST /v1/trust-check
- Live OFAC SDN screening (refreshed daily from U.S. Treasury XML)
- GoPlus token security
- Etherscan source verification
- Anomaly heuristics
- Free /v1/trust-check/preview returns sample fixtures for client testing
- Swap router via /v1/quote
- MCP-native swap router via 0x Settler
- 10bps integrated fee
- Non-custodial

## Pricing

$0.001 USDC per call for trust-check on Base mainnet.

## Integrations

- Swap MCP: https://swap.paladinfi.com/mcp
- GitHub: https://github.com/paladinfi/paladin-swap-mcp
- Health: https://swap.paladinfi.com/health
- x402 payment protocol on Base (eip155:8453)