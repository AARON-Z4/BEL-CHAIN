# Notifications Endpoint

## Purpose
Provides controlled `notifications` operations through `/v1/notifications`.

## Rules
- Authenticate every request.
- Authorize according to RBAC and ABAC policy.
- Validate input and reject unknown fields where applicable.
- Log every state-changing request with actor, target, timestamp, result and correlation ID.
- Return no sensitive fields beyond the caller's authorized scope.

## Example response
```json
{"status":"success","requestId":"req-REPLACE_ME"}
```
