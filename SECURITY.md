# Security Policy

## Reporting A Vulnerability

Do not disclose a suspected vulnerability publicly.

Contact the NexTill supplier or support contact that issued your license. Include:

- A clear description of the issue
- The affected NexTill version
- Reproduction steps
- Expected and observed behavior
- Any relevant sanitized logs

Do not include passwords, license keys, customer information, full invoices, payment data, or database backups.

## Supported Version

Security and reliability fixes are delivered through the latest signed NexTill release. Customers should install the newest available OTA update.

## Operational Security

- Keep Windows and browser updates installed.
- Use separate named staff accounts.
- Use strong, unique passwords.
- Restrict Windows administrator access.
- Keep backups on protected storage.
- Never share license keys or Installation IDs publicly.
- Download setup files only from this repository's official Releases page.
- Verify release checksums when transferring installers through third parties.

## Cloud Data Boundaries

Routine NexTill health reporting contains technical metadata and aggregate record counts. It does not include product details, customer records, invoice contents, passwords, license keys, or full financial data.

Support diagnostics require local administrator approval and are automatically deleted after their retention period.
