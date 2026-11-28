## Overview

σ-gate Coherence Scorer is an x402-payable API endpoint that evaluates LLM-generated text for coherence and hallucination.

## How It Works

1. Agent sends `GET /check?text=...`
2. Endpoint returns HTTP 402 with a price of 0.001 USDC on Solana
3. Agent pays and re-calls with `&tx=`
4. No account, no KYC required; non-custodial settlement to a Solana wallet

## Pricing

0.001 USDC per check on Solana. Pay-per-call via x402.

## Deployment

Hosted on Azure Container Apps and Hugging Face Spaces.