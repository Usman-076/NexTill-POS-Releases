<p align="center">
  <img src="assets/nextill-logo.png" alt="NexTill POS" width="220">
</p>

<h1 align="center">NexTill POS</h1>

<p align="center">
  A fast, practical point-of-sale and shop management system built for everyday retail.
</p>

<p align="center">
  <a href="https://github.com/Usman-076/NexTill-POS-Releases/releases/latest"><strong>Download NexTill POS</strong></a>
  &nbsp;|&nbsp;
  <a href="INSTALLATION.md">Installation Guide</a>
  &nbsp;|&nbsp;
  <a href="SUPPORT.md">Support</a>
</p>

---

## Built For The Counter

NexTill keeps the familiar workflow shop staff already understand while replacing slow, dated screens with a responsive interface designed for laptops and desktop checkout stations.

- Quick barcode and product-name checkout
- Live cart updates without page reloads
- Compact layout for 720p and 1080p shop displays
- Responsive controls for laptop and desktop use
- Clear totals, discounts, payments, and customer balances
- Fast server-side invoice and product lists for larger databases

## POS And Checkout

- Barcode scanner and manual product search
- Product variations, quantities, and units
- Per-item quantity and sale-price editing
- Automatic default discounts from shop settings
- Manual price reductions tracked as item discounts
- Cash, card, and mixed payment recording
- Walk-in and registered customer sales
- Transaction-safe checkout and stock deduction
- Live account and payment summaries
- Reset cart and rapid repeat-sale workflow

## Products And Inventory

- Product creation, editing, and soft deletion
- Purchase, market, and sale pricing
- Configurable automatic sale-price markup
- Product variations and quantity units
- Current stock management
- Low-stock monitoring
- Expiry-date monitoring
- Stock transfer and incoming-stock workflow
- Barcode lookup and searchable product catalog
- Paginated product lists for large inventories

## Receipts And Printing

- Professional thermal sale receipts
- Dedicated refund receipts
- Automatic fit to the printer driver's printable width
- Optimized layouts for common 58 mm and 80 mm thermal printers
- Item, quantity, price, discount, and total presentation
- Configurable shop identity and receipt policy
- Long product-name wrapping without breaking numeric columns
- Print-ready borders and row separators

> Set the correct roll width in the Windows printer driver. NexTill automatically uses the printable width supplied by the selected printer.

## Invoices, Refunds And Accounts

- Searchable, paginated invoice history
- Monthly invoice numbering for easier long-term organization
- Date-range invoice filters
- Invoice payment-status updates
- Partial and full refunds
- Automatic stock restoration on refunds
- Refund history and printable return receipts
- Customer balances and account statements
- Historical pricing preserved on invoice items

## Reports

- Profit and loss statement
- Top-selling products
- Expenditure statement
- Overall business statement
- Date-range filtering
- Sales, cost, expense, and payment summaries
- Efficient queries designed for growing shop databases

## Customers, Expenses And Staff

- Customer profiles and balances
- Customer search directly from checkout
- Expense recording and payment status
- Username and password staff login
- Modern password hashing with legacy-account upgrade
- User management and protected administrative actions
- Session, CSRF, and authenticated AJAX protections

## Updates, Licensing And Reliability

- Guided Windows installer with bundled Apache, PHP, and MariaDB
- No separate XAMPP installation required
- Windows services configured for automatic startup
- Desktop and Start menu shortcuts
- License activation tied to the installation
- Offline-valid signed licenses
- Signed OTA updates from inside NexTill
- Package hash and RSA signature verification before installation
- Database and application rollback backup during updates
- License, settings, shop data, and backups preserved across OTA updates
- Manual database backup support

## NexTill Owner Control Center

Licensed installations can securely connect outbound to the NexTill cloud service:

- Shop online/offline status
- Installed version and update visibility
- Technical health summaries
- License issuance, renewal, suspension, and history
- In-app customer feedback and support replies
- Offline feedback queue with automatic retry
- Shop-approved diagnostic requests
- Private, time-limited diagnostic storage
- Staff roles, MFA protection, and security audit history

NexTill does not upload product details, customer records, invoice contents, passwords, license keys, or full financial data as part of routine health reporting.

## Download

### New Installation

[**Download NexTill POS Setup 1.0.19**](https://github.com/Usman-076/NexTill-POS-Releases/releases/download/v1.0.19/NexTill-POS-Setup-1.0.19.exe)

Use the Windows setup program for a new shop computer. It installs and configures the complete local server environment.

### Existing Installation

Open **Dashboard → System Update** inside NexTill. The built-in updater downloads only signed application packages and preserves local shop data.

The ZIP asset on the release page is intended for NexTill's authenticated in-app updater, not manual extraction.

## System Requirements

- Windows 10 or Windows 11, 64-bit
- Laptop or desktop computer
- Recommended display resolution: 1366×768 or higher
- 4 GB RAM minimum; 8 GB recommended
- Approximately 1 GB free disk space plus room for shop data and backups
- Chrome, Edge, or another current Chromium-based browser
- Optional USB barcode scanner and Windows-compatible thermal printer
- Internet required for activation, updates, and cloud support features
- Normal POS operation remains local and can continue without internet

## Getting Started

1. Download the latest setup executable.
2. Run setup as an administrator.
3. Open NexTill using the desktop shortcut.
4. Send the displayed Installation ID to your NexTill supplier.
5. Enter the license key you receive.
6. Sign in and configure shop, pricing, receipt, printer, and backup settings.

See the complete [Installation Guide](INSTALLATION.md).

## Security And Privacy

NexTill uses signed licensing, signed update packages, authenticated local actions, CSRF protection, transaction-safe sales/refunds, outbound-only cloud communication, and explicit approval before diagnostic collection.

Read [SECURITY.md](SECURITY.md) for reporting and operational guidance.

## Commercial License

NexTill POS is commercial software. Download availability does not grant an unrestricted license to use, redistribute, resell, modify, or reverse engineer the software. A valid license key is required.

See [LICENSE.md](LICENSE.md).

## Support

Licensed customers can submit feedback from **Settings → Feedback & Support** inside NexTill. For installation and activation help, see [SUPPORT.md](SUPPORT.md).

---

<p align="center">
  <strong>NexTill POS</strong><br>
  Modern checkout. Practical shop control.
</p>
