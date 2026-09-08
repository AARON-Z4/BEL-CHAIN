# Non-Functional Requirements

## Security
- TLS for data in transit; strong encryption for data at rest.
- No plaintext private keys or restricted files in source control or ledger state.
- Multi-approval for defined high-risk actions.

## Performance
- Indexed dashboard queries should normally complete within three seconds.
- Access verification should normally complete within one minute.

## Availability
- Support backups, node failover, recovery testing, and monitoring.

## Usability
- Show only authorized navigation/actions.
- Require confirmation for destructive or privileged actions.
- Provide responsive and accessible UI.

## Auditability
- Every critical action must include actor, action, target, timestamp, result, and transaction/evidence identifier.
