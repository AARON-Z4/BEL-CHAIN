# Component Architecture

| Component | Responsibility |
|---|---|
| Web Dashboard | Role-aware user interface |
| API Gateway | API authentication, validation, orchestration |
| Identity Service | DID and credential workflows |
| Policy Service | RBAC/ABAC decisions and approval workflows |
| Asset Service | Passport, transfer, custody, quality and maintenance workflows |
| Fabric Gateway | Submits/evaluates chaincode transactions |
| Event Worker | Consumes ledger events and updates index database |
| Report Service | Produces audit exports |
| Storage Service | Encrypts/stores documents and returns content hash |
| Integration Adapters | ERP, RFID/QR, SIEM and notification connectors |
