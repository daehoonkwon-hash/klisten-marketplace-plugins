# DeadlineEngine — Cursor client

Calculate and compare supplied dates under supported rules. No legal deadline certification.

This package uses Cursor's supported plugin variable schema and bearer header. In Plugins → Configure, set `KLISTEN_API_KEY` to your own existing key with only `deadline:compute and deadline:diff`. The secret is not stored in this package and is sent only to `https://api.klisten.co.kr/mcp/deadlineengine`. A 0 USD capped key is recommended for free checks. Never paste secrets in chat.

The server enforces the key's organization, permissions and service prerequisites. Installation does not grant permissions, buy a scan, issue a content license or fund an account. Existing OAuth clients and other installed connections are unchanged.

Use `tools/list` to inspect the current server schema before a call. Expected bounded inventory: `deadline_compute and deadline_diff`. ClearGate needs an existing unexpired free grant; AgentScore needs an existing activity owned by the originating key; ActionCheck needs an owner policy. Do not create a paid prerequisite for a test.

Configuration and JSON checks are complete. Native Cursor installation and authenticated execution of this exact package remain unverified; marketplace acceptance is separate. See `readiness.json`.

This package contains only public client configuration, setup instructions, documentation, and an icon. It does not contain a backend engine or database. The MIT license in LICENSE applies only to the contents distributed in this package. It does not license the Klisten server, hosted API implementation, databases, private code, or other materials outside this package. Access to hosted services remains subject to their applicable terms and authorization.

Publisher: Klisten Inc. Product information: https://klisten.co.kr/products. Documentation: https://klisten.co.kr/docs.html. Support: https://klisten.co.kr/customer-guide.html. Privacy: https://klisten.co.kr/privacy.html. Terms: https://klisten.co.kr/terms.html.
