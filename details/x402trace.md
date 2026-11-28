## Overview

x402trace is a local CLI debugger for x402 on Base. It detects timeout-reconciliation gaps (the #1062 settled-but-server-thinks-not pattern), validates .well-known/x402 + Bazaar listings (the #2207 cluster), diffs facilitators, and explains 402s offline.

## Features

- Detects timeout-reconciliation gaps
- Validates .well-known/x402 manifest
- Validates Bazaar listings
- Diffs facilitators
- Explains 402 responses offline
- Read-only, no key handling
- Supports Sepolia + Base mainnet

## Pricing

Open source, free to use.

## Deployment

Local CLI tool via `npx x402trace`

## Links

- [npm](https://www.npmjs.com/package/x402trace)
- [GitHub](https://github.com/fardinvahdat/x402trace)