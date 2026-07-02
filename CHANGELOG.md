# NexTill POS Changelog

## 1.0.19 - 2026-07-02

### Installation And Reliability

- Improved bundled Apache, PHP, and MariaDB setup.
- Added automatic Windows services, launcher health checks, and service recovery.
- Improved customer setup packaging and protected internal tooling.

### Updates And Security

- Added signed OTA packages with SHA-256 and RSA verification.
- Added update progress steps, rollback backups, and protected-file validation.
- Preserved databases, licenses, settings, credentials, and backups during updates.
- Strengthened authenticated routes, CSRF handling, password storage, and request validation.

### POS And Design

- Modernized the laptop and desktop interface.
- Improved live cart, product, invoice, and modal updates.
- Added configurable sale-price markup and automatic/manual discount tracking.
- Improved large product and invoice list performance.
- Rebuilt thermal sale and refund receipts for common printer widths.
- Improved invoice numbering, refunds, reports, stock handling, and account statements.
