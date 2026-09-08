# Functional Requirements

## Identity
- FR-ID-01: Create a unique DID for each authorized employee, supplier, device, system, and asset.
- FR-ID-02: Issue, verify, suspend, revoke, and recover credentials.
- FR-ID-03: Record identity lifecycle events immutably.

## Access control
- FR-AC-01: Support Admin, Manager, Project Manager, Auditor, Operator, Supplier, and Stakeholder roles.
- FR-AC-02: Enforce RBAC permissions in backend and chaincode workflows.
- FR-AC-03: Evaluate ABAC fields: organization, unit, project, clearance, asset classification, location, time, and status.
- FR-AC-04: Support access request, approval, rejection, expiry, and revocation.

## Assets
- FR-AS-01: Mint a unique asset passport.
- FR-AS-02: Link asset to serial/RFID/QR, manufacturer, owner, custodian, project, and status.
- FR-AS-03: Support controlled ownership/custody transfers.
- FR-AS-04: Anchor hashes for certificates, reports, maintenance records, and documents.

## Audit
- FR-AU-01: Log identity, policy, asset, access, custody, QC, and maintenance events.
- FR-AU-02: Search and filter audits.
- FR-AU-03: Export PDF/CSV audit reports.
