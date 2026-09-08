# Technology Decisions

| Decision | Choice | Reason |
|---|---|---|
| Ledger | Hyperledger Fabric | Permissioned membership, policies and private-data support |
| Identity | DID + Verifiable Credentials + Fabric CA | Portable identity model plus enterprise certificate controls |
| Access | RBAC plus ABAC | Simple roles with context-aware restrictions |
| Asset records | NFT-style chaincode assets | Unique lifecycle/provenance records without public-token dependency |
| Documents | Encrypted off-chain storage | Privacy, file-size and retention control |
| Search | PostgreSQL index | Fast UI filters and reporting |
| UI | React + TypeScript | Component-based role-aware dashboard |
