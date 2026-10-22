---
name: setup
description: Connect SchemaShield with its product-specific public OAuth client.
---

Inspect the configured schemashield HTTP MCP server and readiness.json. Authenticate through the host's OAuth flow using the user's own authorized Klisten account; no password, token or API key belongs in chat or package files.

The connection requests only schema:read and schema:write. Verify tools/list and the current tool input/output schemas before using any tool. Do not invent identifiers or report unrun checks as successful. Explain any tool's effects and obtain the user's authorization before performing their work. Hosted service access and charges follow the applicable Klisten terms.

SchemaShield stores and compares only JSON schema documents supplied by the user. Listing targets, reading a baseline and retrieving a snapshot return previously submitted organization data. They do not discover databases or establish a live database inventory or its current schema. SchemaShield cannot discover, connect to or query live databases, fetch URLs, or retrieve current schemas. A live-database discovery request therefore requires another authorized data source; a SchemaShield comparison requires the user to supply the JSON document.
