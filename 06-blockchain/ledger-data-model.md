# Ledger Data Model

## Keys
- `DID:<did>` — DID state and status
- `VC:<credentialId>` — credential metadata/status
- `ROLE:<roleId>` — role definition
- `POLICY:<policyId>` — versioned policy
- `ASSET:<assetId>` — asset passport
- `CUSTODY:<assetId>:<eventId>` — custody record
- `AUDIT:<eventId>` — immutable audit event

## Audit event
```json
{
  "eventId":"AUDIT-00001",
  "type":"ASSET_MINTED",
  "actorDid":"did:bel:fabric:manager-001",
  "targetId":"BEL-ASSET-2026-000001",
  "timestamp":"2026-09-08T00:00:00Z",
  "result":"SUCCESS",
  "txId":"fabric-transaction-id",
  "evidenceHash":"sha256:REPLACE_ME"
}
```
