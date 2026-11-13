---
name: setup
description: Connect Klisten dealgate and use its documented bounded tools.
---

Use the MCP server declared in this package. Sign in to the existing Klisten account and approve only dealrate:price. Never ask for raw API keys, passwords or OAuth tokens in chat.

Use tools/list to confirm dealrate_price and inspect current schemas before a call. Do not invent tenant IDs or report an operation that was not run.

Calculate indicative quotes from supplied deal inputs. No negotiation, checkout or money movement.

Review proposed writes or executions before use. Reuse exact request keys for retries. Stored results describe only the recorded test, not a live operational guarantee.

This package uses the existing public OAuth client. It does not create clients, extend permissions, make payments or certify marketplace approval. See readiness.json for host verification limits.
