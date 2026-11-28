## Overview

unlock-api is a pay-per-unlock website fetcher that returns rendered body, screenshots, or full XHR captures through a stealth browser and residential proxy.

## Features

- POST /unlock endpoint
- Rendered body, screenshot, or full XHR capture
- Stealth browser + residential proxy
- Conditional settlement: payment only when expect_status / expect_contains checks pass
- Failed unlocks return 502 and are not charged
- No API key required

## Pricing

$0.02 USDC per call on Base.

## Deployment

Cloud-hosted on Cloudflare Workers.