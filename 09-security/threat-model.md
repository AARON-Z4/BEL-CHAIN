# Threat Model

| Threat | Example | Primary controls |
|---|---|---|
| Credential theft | Compromised user key | MFA, HSM, key rotation, DID suspension/revocation |
| Insider abuse | Unauthorized role grant | Segregation of duties, multi-approval, audit alerts |
| Counterfeit asset | Fake component record | RFID/QR binding, issuer verification, QC approval |
| Sensitive data exposure | Restricted file in ledger | Encrypted off-chain storage; ledger hashes only |
| Chaincode defect | Incorrect transfer logic | Reviews, tests, access checks, endorsement policy |
| Node compromise | Peer infrastructure breach | Network segmentation, TLS, monitoring, hardened hosts |
| API abuse | Brute force or injection | Rate limits, validation, authz middleware, logs |
| Key loss | Employee loses key | Controlled recovery and credential reissuance |
