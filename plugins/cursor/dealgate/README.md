# dealgate — Cursor client

Calculate an indicative quote from supplied synthetic deal inputs.

Quote calculation only. Does not negotiate, accept offers, execute checkout, move money or contact counterparties.

Connect the existing Klisten account using the declared public OAuth client. No client secret is required. Keep the raw API key and review credentials out of chat and this package. Connecting makes no payment and does not change spending limits.

Expected tools: dealrate_price. Inspect the actual tool schemas before use. An account needs the product scope and owner-provisioned prerequisites; unsupported profiles fail closed.

Evidence: Actual Claude supplied-input quote checks and official Cursor OAuth/native project MCP inventory verified on 2026-10-24. This is MCP connection/runtime evidence, not evidence that this exact plugin package has been installed or approved by the marketplace. See readiness.json.

Documentation: https://klisten.co.kr/dealgate

This package contains only public client configuration, setup instructions, documentation, and an icon. It does not contain a backend engine or database. The MIT license in LICENSE applies only to the contents distributed in this package. It does not license the Klisten server, hosted API implementation, databases, private code, or other materials outside this package. Access to hosted services remains subject to their applicable terms and authorization.

Publisher: Klisten Inc. Product information: https://klisten.co.kr/products. Documentation: https://klisten.co.kr/docs.html. Support: https://klisten.co.kr/customer-guide.html. Privacy: https://klisten.co.kr/privacy.html. Terms: https://klisten.co.kr/terms.html.
