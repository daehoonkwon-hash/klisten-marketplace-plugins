---
name: setup
description: Set up AgentEscrow and inspect its available tools.
---

Confirm the configured server and authentication with the user. Never request secret values in chat.
Use tools/list to confirm the inventory below before calling a tool. Explain required organization identifiers and prerequisites from input schemas. Do not invent tenant IDs or claim an unrun operation succeeded.

Included services: agentescrow, proof.

- `agentescrow_verifyEscrowEvidence`
- `proof_ingest_claim`
- `proof_collect_evidence`
- `proof_verify`
- `proof_issue_receipt`
- `proof_verify_receipt`
- `proof_needs_human_review`

Inspect tools/list input schemas for all inputs. Parent extensions are included here once; do not install them as separate products.

This candidate has no active MCP connection. Do not claim the listed operations are currently available. Follow readiness.json; do not activate staged parent settings or invent an endpoint.
