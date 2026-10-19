---
name: klisten-vectorevict-setup
description: Configure the Klisten VectorEvict hosted MCP client and verify product-scoped discovery.
---

Use the included .mcp.json configuration with the registered Claude public OAuth client. Complete interactive sign-in and consent in the host. No client secret or API key is supplied by this package. Request only `vectorevict:evaluate` and connect only to `https://api.klisten.co.kr/mcp/vectorevict`.

After authorization, verify the exact tools in expected-tools.json. Run a benign caller-supplied fixture with vectorevict_registerVector; report the actual output. Do not describe an unrun fixture as tested. Ask for missing required fields, reject malformed inputs, and retain uncertainty in draft results.

Calculate vector lifecycle tiers and eviction plans from supplied metadata. This client does not delete vectors or access storage.

Do not claim this package is marketplace-submitted, marketplace-approved or natively installed. MIT applies only to the distributed client materials; it does not license hosted engines or databases. Do not copy or request server source, database content, passwords, tokens or unrelated product scopes.
