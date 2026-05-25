# RTK Context Compressor

RTK Context Compressor is a hosted remote MCP for OpenAI Codex context compressor.

This repository is a public documentation project for RTK Context Compressor. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://rtkcontext.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=rtkcontext_public_docs&utm_content=readme_home
- Pricing: https://rtkcontext.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=rtkcontext_public_docs&utm_content=readme_pricing
- Checkout: https://rtkcontext.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=rtkcontext_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://rtkcontext.clauxel.com/mcp
- Server card: https://rtkcontext.clauxel.com/server-card.json
- Registry name: `com.clauxel.rtkcontext/rtkcontext-mcp`
- Tools: `compress_context_for_task`, `estimate_context_savings`, `issue_context_receipt`, `read_compression_history`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: compress_context_for_task
- MCP tool: estimate_context_savings
- MCP tool: issue_context_receipt
- MCP tool: read_compression_history

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
