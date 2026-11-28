## Overview

Agent402 MCP is a hosted MCP connector for the Agent402 server (~1,100 deterministic web tools).

## Features

- Four meta-tools: search_tools, find_tool, call_tool, about_agent402
- Agent discovers and invokes full catalog without bloating its tool list
- Dual-rail payment: free via proof-of-work for pure-CPU tools
- Paid via x402 USDC on Base/Polygon/Arbitrum for non-CPU tools
- No LLM in the serving path
- Categories: browser, search, PDF/image/OCR/audio, geo, live data (FX, weather, USGS, gov-data), network truth (DNS/TLS/WHOIS), crypto/x402 helpers, ~1,040 pure-CPU utilities
- Self-hostable
- Distributed as the agent402-mcp stdio package
- Registered with official MCP Registry as io.github.MikeyPetrillo/agent402

## Pricing

- Free via proof-of-work for pure-CPU tools
- Paid via x402 USDC on Base/Polygon/Arbitrum for other tools

## Deployment

Cloud-hosted MCP server; self-hostable via npm package.

## Links

- GitHub: https://github.com/MikeyPetrillo/Agent402
- OpenAPI: https://agent402.tools/openapi.json
- Discovery: https://agent402.tools/.well-known/x402
- npm: https://www.npmjs.com/package/agent402-mcp
- MCP Registry: io.github.MikeyPetrillo/agent402