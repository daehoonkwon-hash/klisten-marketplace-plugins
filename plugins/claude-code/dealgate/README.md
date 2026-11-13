# DealGate — Claude Code client

Calculates indicative quotes from supplied inputs; no negotiation, checkout, counterparty contact or money movement.

The package declares the existing DealGate public OAuth client and fixed localhost:8080 callback in `.mcp.json`. No new OAuth client, permission or server configuration is created by this package.

Install from the existing source marketplace:

```text
/plugin install klisten-dealgate --marketplace daehoonkwon-hash/klisten-marketplace-plugins
```

Sign in to your existing Klisten account, select an eligible scoped key and review the requested permissions. A valid service operating window and any required owner-provisioned fixture must already exist. Installing or reconnecting does not renew access or fund an account.

The official Claude Code manifest validator passed on 2026-11-14. Authenticated execution of this exact Claude Code package and marketplace approval have not yet been verified; `submissionReady` remains false in `readiness.json`. Do not treat source validation as a completed workflow or listing.

This package contains only public client configuration, setup instructions, documentation, and an icon. It does not contain a backend engine or database. The MIT license in LICENSE applies only to the contents distributed in this package. It does not license the Klisten server, hosted API implementation, databases, private code, or other materials outside this package. Access to hosted services remains subject to their applicable terms and authorization.

Publisher: Klisten Inc. Product information: https://klisten.co.kr/products. Documentation: https://klisten.co.kr/docs.html. Support: https://klisten.co.kr/customer-guide.html. Privacy: https://klisten.co.kr/privacy.html. Terms: https://klisten.co.kr/terms.html.
