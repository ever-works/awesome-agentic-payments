## Overview

anchor-x402-mcp is an MCP server providing agent payment and utility tools for anchor-x402 on Base and Solana.

## Features

- 16 MCP tools
- 9 commodity primitives: anchor, screen, attest, decode/tx, resolve/name, price/token, decode/calldata, parse/datetime, intel/wallet
- 1 async due-diligence investigator (/v1/investigate, $7.77)
- 1 verifiable signed RNG (/v1/roll)
- 5 universal LLM endpoints: roast, oracle (on-chain anchored verdict), tldr, aura, grade
- Auto-pays from agent's Base wallet via x402-fetch + viem
- No prepay, no API key, no account
- Works with Claude Desktop, Claude Code, Codex CLI, ChatGPT Desktop, Cursor, OpenAI Agents SDK
- Usage: `npx -y anchor-x402-mcp`

## Pricing

- /v1/investigate: $7.77
- Other tools: x402 payments via Base wallet

## Deployment

npm package (MCP server).