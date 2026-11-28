## Overview

InboxPolicy provides send-decision email verification for AI agents. Instead of returning a raw status field, one call returns an action — send / send_with_caution / review / retry_later / avoid — with confidence and SMTP/DNS evidence.

## Features

- Send-decision email verification
- Action outputs: send, send_with_caution, review, retry_later, avoid
- Confidence scoring
- SMTP/DNS evidence
- x402 pay-per-call at $0.01 USDC on Base
- Batch pricing: one payment per batch of up to 5,000 emails
- No account required
- Hosted MCP server at https://mcp.inboxpolicy.com
- MCP tools: decide_send, verify_email, batch

## Pricing

$0.01 USDC per call via x402 on Base. Batch pricing available for up to 5,000 emails per payment.

## Deployment

Cloud-hosted API service with hosted MCP server.

## Documentation

https://inboxpolicy.com/docs