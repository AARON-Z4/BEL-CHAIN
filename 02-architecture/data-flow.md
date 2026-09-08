# Data Flow

## Asset creation
1. Authorized manager submits metadata and supporting document.
2. API validates identity and policy.
3. Storage service encrypts the file and returns a hash/reference.
4. API invokes chaincode to mint asset passport.
5. Ledger emits event; worker indexes it.
6. Dashboard displays traceable asset record.

## Access decision
1. User authenticates using DID/SSO session.
2. API evaluates RBAC and ABAC attributes.
3. For privileged access, workflow obtains required approvals.
4. Decision and reason are logged.
5. Authorized encrypted resource is released via time-bound link or session.
