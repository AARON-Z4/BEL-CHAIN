# Trust Boundaries

- **User boundary:** browsers, mobile devices, supplier endpoints; assume untrusted until authenticated.
- **Application boundary:** API validates all input, authorizes each action, and logs security events.
- **Ledger boundary:** only recognized organizations/identities submit transactions.
- **Storage boundary:** documents are encrypted and accessible only after policy authorization.
- **Integration boundary:** ERP/RFID/SIEM adapters use scoped credentials, validation, and message signing where supported.
- **Administration boundary:** network/policy administration requires separation of duties and enhanced approval.
