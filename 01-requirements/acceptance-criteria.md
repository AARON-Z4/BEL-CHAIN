# Acceptance Criteria

## Identity creation
- Admin can create a DID and issue a role credential.
- DID registration produces a ledger transaction and audit event.

## Asset minting
- Only authorized roles can create asset passports.
- Duplicate serial/RFID values are rejected.
- Asset creation produces provenance and audit records.

## Access request
- Unauthorized users cannot directly access restricted resources.
- A request can be approved/rejected by authorized approvers.
- Decision is recorded with reason, approver, timestamp, and policy version.

## Audit verification
- Auditor can search events and open transaction evidence.
- Tampered document content fails hash validation.
