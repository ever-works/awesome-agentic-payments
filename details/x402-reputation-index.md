## Overview

x402 Reputation Index provides endpoint-side reputation with independent verified-delivery verdicts for the x402 catalog.

## Features

- Independent verified-delivery verdicts for ~10k Base+USDC endpoints
- Probes every 402 handshake
- Attributes settlements via facilitator-sender filtering with payTo-collision detection
- Flags wash/honeypots (pay-then-401)
- Pay-tests endpoints with real USDC
- Top verdict tier requires confirmed delivery
- Free rate-limited HTTP API
- Remote MCP: claude mcp add --transport http x402-reputation https://x402rep.invoitech.com/mcp
- Live stats at /api/v1/status

## Pricing

Free rate-limited HTTP API.

## Deployment

Web service at x402rep.invoitech.com

## MCP

https://x402rep.invoitech.com/mcp

## Status

https://x402rep.invoitech.com/api/v1/status