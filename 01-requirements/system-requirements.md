# System Requirements

## Development
- Node.js LTS, pnpm/npm, Docker, Docker Compose.
- Go toolchain for Fabric chaincode.
- PostgreSQL and S3-compatible MinIO for local development.

## Production baseline
- Linux nodes for Fabric peers/orderers and CA.
- Segmented network, TLS certificates, secure secrets manager, HSM where available.
- PostgreSQL high availability and encrypted object storage.
- Centralized logs, monitoring, alerts, and backup service.
