# ADR-003: Keep Sensitive Content Off-Chain

## Decision
Store confidential documents and large files in encrypted approved storage; anchor their hashes and metadata on-chain.

## Rationale
Ledger immutability conflicts with deletion/retention needs and is unsuitable for confidential large files.

## Consequences
The application must validate hash integrity and protect storage encryption keys.
