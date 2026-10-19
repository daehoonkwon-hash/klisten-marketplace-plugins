---
name: setup
description: Set up LocalBusinessLayer and inspect its available tools.
---

Confirm the configured server and authentication with the user. Never request secret values in chat.
Use tools/list to confirm the inventory below before calling a tool. Explain required organization identifiers and prerequisites from input schemas. Do not invent tenant IDs or claim an unrun operation succeeded.

Included services: localbus.

- `localbus_registerSource`
- `localbus_defineSchema`
- `localbus_access`
- `localbus_auditLog`

Inspect tools/list input schemas for all inputs. Parent extensions are included here once; do not install them as separate products.

This is a local configuration candidate. This build has not verified installation or execution in this host. Use the user-controlled OAuth approval flow; never request raw keys or passwords in chat.
