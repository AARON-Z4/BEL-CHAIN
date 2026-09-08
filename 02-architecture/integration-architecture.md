# Integration Architecture

## ERP
Synchronize approved asset identifiers, unit/project metadata, and workflow status through API or scheduled secure export. BEL-Chain does not replace ERP.

## RFID/QR
Map physical label IDs to asset passport IDs. Scan events are validated before custody/maintenance updates.

## SIEM
Forward selected audit and security events: failed authorization, policy changes, identity revocation, transfer anomalies, and administrative actions.

## Document management
Encrypt documents off-chain; persist only hash, version, classification, and retrieval reference in ledger state.
