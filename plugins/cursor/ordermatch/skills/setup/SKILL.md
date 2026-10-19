---
name: klisten-ordermatch-setup
description: Configure the Klisten OrderMatch hosted MCP client and verify product-scoped discovery.
---

Use the included mcp.json configuration with the registered Cursor public OAuth client. Complete interactive sign-in and consent in the host. No client secret or API key is supplied by this package. Request only `ordermatch:evaluate` and connect only to `https://api.klisten.co.kr/mcp/ordermatch`.

After authorization, verify the exact tools in expected-tools.json. Run a benign caller-supplied fixture with ordermatch_ingestPo; report the actual output. Do not describe an unrun fixture as tested. Ask for missing required fields, reject malformed inputs, and retain uncertainty in draft results.

Compare supplied purchase orders and acknowledgements and report discrepancies. This client does not submit or amend orders.

Do not claim this package is marketplace-submitted, marketplace-approved or natively installed. MIT applies only to the distributed client materials; it does not license hosted engines or databases. Do not copy or request server source, database content, passwords, tokens or unrelated product scopes.
