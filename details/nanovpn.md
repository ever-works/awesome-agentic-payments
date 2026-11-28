## Overview

NanoVPN is a pay-per-request geo-located web egress service for AI agents that uses x402 for USDC payments.

## Features

- Agent pays USDC via x402
- Node in chosen city fetches target URL
- Returns HTTP status, bytes, and node's egress IP (geo proof)
- Verify → fetch → settle model; failed fetch is never charged
- 17 nodes across 6 continents
- ~$0.001/request or per-GB
- Settled as Circle Gateway nanopayments on Arc testnet

## Pricing

~$0.001 per request or per-GB via x402.

## Deployment

Web application at nanovpn-web.vercel.app/use-with-agent

## Nodes/Prices

https://nanovpn-web.vercel.app/api/nodes