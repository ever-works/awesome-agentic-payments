## Overview

x402-spendguard is a client-side spend firewall for agents paying via x402.

## Features

- Enforces deterministic policy before payment is signed
- Destination allowlist
- Per-request/domain/global caps
- Binding checks: signed value, recipient, asset, and capability lifetime must match the 402 challenge
- Mechanism-not-policy (no reputation scoring or heuristics)
- Fail-closed
- Durable cross-process spend accounting
- Tamper-evident decision log
- TypeScript
- MIT license
- Zero runtime dependencies
- No network egress
- Pre-alpha and testnet-validated (Base Sepolia)
- Not yet for mainnet

## Pricing

Open source, free to use.

## License

MIT

## Repository

https://github.com/x402spendguard/x402-spendguard

## npm Package

https://www.npmjs.com/package/x402-spendguard