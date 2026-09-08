# ADR-005: Combine RBAC and ABAC

## Decision
Use RBAC for baseline permissions and ABAC for contextual restrictions.

## Rationale
Roles simplify administration while attributes enforce project, unit, clearance, location, classification, and time restrictions.

## Consequences
Policy evaluation and testing require explicit attribute schemas and deny-by-default behavior.
