## Overview

DeadDrop is a one-time secret relay for humans and AI agents built on the x402 payment protocol. It enables paid, ephemeral secret sharing with client-side encryption.

## Features

- One-time secret sharing: POST a secret, get a self-destructing link
- Payment: $0.01 USDC on Base via x402
- Client-side AES-GCM encryption; server stores only ciphertext
- No accounts required
- Reading is free
- MCP Server available for AI agent integration

## Pricing

- Secret submission: $0.01 USDC on Base via x402
- Reading: Free

## Deployment

Self-hosted via MCP server repository.

## Integrations

- MCP Server: https://github.com/jerrywrongalot-byte/deaddrop-mcp