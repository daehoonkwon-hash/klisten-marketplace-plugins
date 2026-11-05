AgentScore isolated synthetic review - local verification evidence

This 30-second video is an edited text-card replay of selected fields returned by the actual local OAuth -> MCP SDK -> original AgentScore signing/source-verification core test on November 5, 2026 UTC. It is not a screen recording, a Claude/GPT conversation, a live scanner run, a real payment, or an exact OpenAI saved-version test.

The test used a separate disposable PostgreSQL cluster and test-only signing authority. No production billing/customer records, reviewer keys or production signing keys were used. The public card excludes organization IDs, key IDs, signatures, tokens and passwords.

Observed result: review_environment=isolated_synthetic; live_payment=false; status=active; score=null; issuer=klisten-synthetic-review; scanner_version=synthetic-review-no-scanner. Active describes the validity of this synthetic signed activity, not a safety approval or reputation score. The displayed issued/expiry timestamps are historical and must not be treated as current access.

Also verified locally: two independently prepared/probed epochs; current-fixture reads after rotation; prior/foreign fixture denial; failed candidate does not replace the pointer; expired fixtures and fixed fourteen-day cutoff fail closed. Scheduler time was accelerated in the rotation/cutoff tests; fourteen real days did not elapse.

Planned reviewer environment: refresh synthetic fixtures every twelve hours; fixed fourteen-day service lifetime from deployment start. Reviewer reads the current generation, fixture ID and expiry from the dedicated guide before calling agentscore_activity_get. No issuance, scan, payment or write tool is exposed.

At preparation time this endpoint has NOT been deployed or verified in the OpenAI saved app. External OAuth/discovery/metadata scanning must pass before submission. Do not present local evidence as OpenAI-host execution or marketplace approval.
