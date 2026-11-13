---
name: setup
description: Connect Klisten agentsafe and use its documented bounded tools.
---

Use the MCP server declared in this package. Sign in to the existing Klisten account and approve only agentsafe:run agentsafe:health. Never ask for raw API keys, passwords or OAuth tokens in chat.

Use tools/list to confirm agentsafe_run, agentsafe_health and inspect current schemas before a call. Do not invent tenant IDs or report an operation that was not run.

Run registered offline recovery contract tests and read stored results. No live models or safety certification.

Only owner-provisioned immutable offline JavaScript workflows are supported. Check the current enabled period and quota before a run. An expired access window must be renewed by the owner; reconnecting does not renew it.

Review proposed writes or executions before use. Reuse exact request keys for retries. Stored results describe only the recorded test, not a live operational guarantee.

This package uses the existing public OAuth client. It does not create clients, extend permissions, make payments or certify marketplace approval. See readiness.json for host verification limits.
