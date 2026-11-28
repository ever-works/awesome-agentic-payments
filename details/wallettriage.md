## Overview

WalletTriage is a real-time wallet risk check service for AI agents using x402 payments.

## Features

- One x402-paid GET request
- Cross-references address's active ERC20 approvals with live exploit threat feed
- Returns risk score (0-100)
- Returns risk level
- Returns revoke-first findings before agent acts
- $0.01 USDC on Base mainnet
- Stateless, no signup or API key
- MCP server available (npx wallettriage-mcp)
- ElizaOS plugin available (plugin-wallettriage)

## Pricing

$0.01 USDC per check on Base mainnet.

## Deployment

Web service at wallettriage.com

## OpenAPI

https://api.wallettriage.com/openapi.yaml