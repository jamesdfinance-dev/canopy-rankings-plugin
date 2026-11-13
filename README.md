# Canopy Rankings

Review Amazon and Shopify catalog changes and product captures in Claude or ChatGPT. Operated by Meridian Bridge Advisory LLC.

## Connect

Endpoint: https://canopy-rankings.fly.dev/mcp. Streamable HTTP, no authentication.

In Claude or ChatGPT, add a custom remote MCP connection when your plan and workspace allow it. For Claude Code:

```sh
claude mcp add --transport http canopy-rankings https://canopy-rankings.fly.dev/mcp
```

Install from the public marketplace with `claude plugin install canopy-rankings --marketplace jamesdfinance-dev/canopy-rankings-plugin`.

Alternatively, load this package with `claude --plugin-dir ./canopy-rankings` or add its directory as a Claude marketplace. The root plugin.json and mcp.json are the portable OpenAI submission package. The .claude-plugin and .mcp.json files support Claude packaging. Do not edit the endpoint to send data to an untrusted server.

## Try it

- Show a fictional Amazon listing review.
- Give me the CSV format for comparing Shopify catalog changes.
- Compare my two catalog snapshots and show the highest-priority findings.

## Scope and privacy

Only supplied catalog rows and product HTML are processed. No live Amazon data, Seller Central or Shopify login, store publishing, payments, or saved browser reviews. Do not send credentials, customer data or private links. Each file/capture is limited to 256 KB; CSVs are limited to 200 rows. Reviews are not stored in the Canopy database. Assistant-provider retention is separate.

[Privacy](https://canopy-rankings.fly.dev/assistants/privacy) · [Terms](https://canopy-rankings.fly.dev/assistants/terms) · [Support](https://canopy-rankings.fly.dev/assistants/support)

Direct installation is separate from directory approval. Canopy Rankings is independent of Canopy API, Anthropic, OpenAI, Amazon and Shopify.

Copyright 2026 Meridian Bridge Advisory LLC. You may install and redistribute this unmodified integration package with its notices. This permission does not cover the private Canopy application source, trademarks, or third-party services.
