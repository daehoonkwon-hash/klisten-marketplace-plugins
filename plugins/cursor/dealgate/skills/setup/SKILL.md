---
name: setup
description: Connect Klisten dealgate and use its documented bounded tools.
---

Use the MCP server declared in this package. Authenticate through the existing Klisten account and approve only dealrate:price. Never ask for raw API keys, passwords or OAuth tokens in chat.

Confirm the inventory dealrate_price and inspect schemas before a call. Do not invent IDs, claim unrun results or broaden scope.

Quote calculation only. Does not negotiate, accept offers, execute checkout, move money or contact counterparties.

Review proposed writes or executions before use. Reuse exact request keys for idempotency; do not retry uncertain execution with a new key. Stored status is evidence about the stored event only.

Read https://klisten.co.kr/dealgate for provisioning and supported inputs. This package does not grant broader access than the selected key and does not make a payment.
