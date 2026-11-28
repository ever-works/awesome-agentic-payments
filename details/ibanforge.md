## Overview

IBANforge is a compliance API for AI agents focused on European banking with x402 USDC micropayments.

## Features

- IBAN validation (mod-97 + BBAN)
- BIC/SWIFT lookup against 121,197 GLEIF entries with LEI enrichment
- Swiss BC-Nummer / QR-IID lookup (1,190 SIX BankMaster entries)
- EMI / vIBAN / neobank classification
- SEPA Instant + VoP (EU 2024/886) reachability
- OFAC/EU/UN sanctions + FATF risk scoring
- Two transports: stdio via npx -y ibanforge-mcp and Streamable HTTP at api.ibanforge.com/mcp
- $0.003–$0.02 USDC per call on Base
- Free tier: 200 req/month with API key

## Pricing

$0.003–$0.02 USDC per call on Base. Free tier: 200 requests/month with API key.

## Deployment

HTTP API at ibanforge.com; Streamable HTTP MCP at api.ibanforge.com/mcp

## Repository

https://github.com/cammac-creator/ibanforge

## npm Package

https://www.npmjs.com/package/ibanforge-mcp

## MCP Registry

https://registry.modelcontextprotocol.io/v0/servers?search=ibanforge

## x402 Discovery

https://api.ibanforge.com/.well-known/x402