## Overview

agent-discovery-mcp is a minimal MCP server (~250 lines TypeScript) for ERC-8004 agent discovery and x402 payment.

## Features

- Three tools: find_agents_by_skill, get_agent_card, call_agent_with_payment
- find_agents_by_skill via 8004scan public API
- call_agent_with_payment using Coinbase's official x402-fetch
- Direct EOA signing — no smart account, no bundler, no relay
- Works with Claude Code, OpenClaw, Cursor, and any MCP-compatible client
- USDC on Base/Ethereum + testnets
- MIT license

## Pricing

- Free and open source under MIT license

## Deployment

Self-hostable; npm package available.

## Links

- Repository: https://github.com/Claynsn/agent-discovery-mcp