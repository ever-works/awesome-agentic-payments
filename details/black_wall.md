## Overview

BLACK_WALL is a pre-signature payment-risk oracle for x402 agents.

## Features

- One call returns GO / HOLD / STOP verdict for paying a counterparty
- OFAC sanctions screening
- Counterparty reputation check
- Price-anomaly detection
- Independently-verifiable Ed25519 signed receipt
- Verdict only, never custody
- Free under $10 at risk, x402-payable above

## Integrations

- Remote MCP tool (`forecast_payment`)
- npm package (`blackwall-mcp`)
- MCP endpoint: https://mcp.blackwalltier.com
- Demo: https://check.blackwalltier.com/demo
- GitHub: https://github.com/bluetieroperations-create/blackwall-mcp

## Pricing

Free under $10 at risk; x402-payable above that threshold.