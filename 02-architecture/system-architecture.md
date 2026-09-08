# System Architecture

BEL-Chain follows a hybrid architecture:

```text
Users / RFID / ERP / SIEM
          |
          v
Web Dashboard (React)
          |
          v
API Gateway + Identity + Policy + Asset + Audit Services
          |                     |
          v                     v
Hyperledger Fabric        PostgreSQL Event Index
          |                     |
          v                     v
Private Data Collections  Encrypted Object Storage
```

The ledger retains authoritative identity state, policy references, asset lifecycle events, and evidence hashes. PostgreSQL supports fast search/reporting; encrypted object storage retains documents and large files.
