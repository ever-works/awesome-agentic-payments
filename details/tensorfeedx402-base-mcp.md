## Overview

@tensorfeed/x402-base-mcp is an MCP server that provides read-only access to Base mainnet blockchain data, specifically designed for verifying x402 payment receipts.

## Features

- 11 MCP tools for Base mainnet chain reading
- Verify on-chain USDC settlement matches claimed x402 receipt (recipient + amount)
- Parse publisher /.well-known/x402 manifests
- List recent USDC payments to an address
- Check AFTA federation status
- Generic Base reads
- No private keys, no signing, no broadcasts (verification only)
- Cryptographic provenance via GitHub Actions OIDC
- Usage: `npx -y @tensorfeed/x402-base-mcp`

## Pricing

Not specified (read-only verification service).

## Deployment

npm package; can be run locally or remotely via MCP.