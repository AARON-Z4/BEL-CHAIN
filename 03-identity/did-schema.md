# DID Schema

```json
{
  "id": "did:bel:fabric:employee-0001",
  "controller": "did:bel:fabric:employee-0001",
  "verificationMethod": [{"id":"#key-1","type":"Ed25519VerificationKey","controller":"did:bel:fabric:employee-0001","publicKeyMultibase":"REDACTED"}],
  "service": [{"id":"#belchain","type":"BELChainService","serviceEndpoint":"https://api.example.belchain"}],
  "status": "active"
}
```

DID documents contain public verification material and service references only. Never include private keys, Aadhaar numbers, biometrics, passwords, or classified attributes.
