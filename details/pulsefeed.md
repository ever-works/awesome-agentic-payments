## Overview

PulseFeed is an independent trust & safety oracle and payment guard for x402 that verifies endpoints before payment.

## Features

- Verify any endpoint before payment
- Liveness check
- Uptime/reputation check
- Scam/anomaly scan (payTo hijack between crawls, price bait-and-switch, honeypot/zero payTo, non-USDC asset)
- On-chain receiver profile (does payTo actually hold/receive USDC)
- Continuously audits the whole ecosystem
- Only ~49% of services catalogs call "healthy" actually return a valid x402 challenge
- Drop-in guardFetch(payingFetch) blocks dead/scam endpoints before payment (zero deps)
- Free /verify + live /status observatory
- Paid /trust deep check
- Live Security Disclosures feed (receiver hijacks, bait-and-switch, honeypots with on-chain proof)
- Cross-domain Data API (x402 + MCP trust data in one call)

## Pricing

Free /verify and /status; paid /trust deep check.

## Deployment

Web service at pulsefeed.dev

## npm Packages

- guard SDK: https://www.npmjs.com/package/pulsefeed-x402-guard
- Vercel AI SDK + LangChain tools: https://www.npmjs.com/package/pulsefeed-x402-ai-tools
- MCP: https://www.npmjs.com/package/pulsefeed-x402-mcp

## Disclosures

https://pulsefeed.dev/incidents

## Data API

https://pulsefeed.dev/data

## Observatory

https://pulsefeed.dev/status