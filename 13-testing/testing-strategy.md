# Testing Strategy

| Layer | Tests |
|---|---|
| Unit | Validators, policy evaluators, UI components, services |
| Chaincode | Role checks, asset state transitions, duplicates, transfers, event emission |
| Integration | API-to-Fabric, database indexer, storage hash verification |
| E2E | DID creation, role grant, asset mint, custody transfer, QC upload, audit report |
| Security | Authorization bypass, expired/revoked credentials, injection, secret scanning |
| Performance | Concurrent asset lookup, audit filtering, transaction workload |
| UAT | Admin, manager, auditor, operator and supplier workflows |

Every release must include denied-access tests and tampered-document hash validation.
