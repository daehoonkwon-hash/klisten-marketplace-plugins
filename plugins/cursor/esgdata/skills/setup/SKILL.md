---
name: klisten-esgdata-setup
description: Configure the Klisten ESGData hosted MCP client and verify product-scoped discovery.
---

Use the included mcp.json configuration with the registered Cursor public OAuth client. Complete interactive sign-in and consent in the host. No client secret or API key is supplied by this package. Request only `esgdata:evaluate` and connect only to `https://api.klisten.co.kr/mcp/esgdata`.

After authorization, verify the exact tools in expected-tools.json. Run a benign caller-supplied fixture with esgdata_defineMetric; report the actual output. Do not describe an unrun fixture as tested. Ask for missing required fields, reject malformed inputs, and retain uncertainty in draft results.

Normalize supplied ESG metric labels and units and check configured ranges. Results do not verify factual source data or submit external reports.

Do not claim this package is marketplace-submitted, marketplace-approved or natively installed. MIT applies only to the distributed client materials; it does not license hosted engines or databases. Do not copy or request server source, database content, passwords, tokens or unrelated product scopes.
