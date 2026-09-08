# Deployment Architecture

## Environments
- Development: local Docker Compose and Fabric test network.
- Staging: isolated organization/channel configuration using masked data.
- Production: segmented, monitored, sovereign/approved infrastructure.

## Production principles
- Separate web, API, worker, database, storage, CA, peer, and ordering workloads.
- Place peer/orderer and databases in protected private networks.
- Enforce TLS, secrets management, least-privilege service accounts, backup, and monitoring.
- Do not expose Fabric peer/orderer administrative endpoints to public networks.
