# Role Permission Matrix

| Action | Admin | Unit Manager | Project Manager | Auditor | Operator | Supplier | Stakeholder |
|---|---:|---:|---:|---:|---:|---:|---:|
| Create DID | Yes | Scoped | No | No | No | No | No |
| Assign role | Yes | Scoped | Project scoped | No | No | No | No |
| Mint asset | Yes | Yes | Scoped | No | No | No | No |
| Transfer ownership | Multi-approval | Scoped | Scoped | View | Request | Confirm | View |
| Add quality evidence | No | No | No | Yes | No | Submit | View |
| Add maintenance event | No | Yes | Yes | View | Yes | No | View |
| View audit | Yes | Unit scoped | Project scoped | Yes | Own events | Own events | Authorized scope |
| Change policy | Yes | Scoped | No | No | No | No | No |

All permissions remain subject to ABAC conditions and deny-by-default policy evaluation.
