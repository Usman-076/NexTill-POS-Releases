# NexTill POS Installation

## Before You Start

- Use a 64-bit Windows 10 or Windows 11 computer.
- Sign in with a Windows administrator account.
- Close any older NexTill setup or server windows.
- Keep the computer connected to the internet for activation.

## Install

1. Download `NexTill-POS-Setup-1.0.19.exe` from the [latest release](https://github.com/Usman-076/NexTill-POS-Releases/releases/latest).
2. Right-click the installer and choose **Run as administrator**.
3. Follow the setup wizard and keep the recommended installation folder.
4. Allow setup to install the required Microsoft runtime if requested.
5. Wait while NexTill configures Apache, MariaDB, the database, startup services, and shortcuts.
6. Launch **NexTill POS** from the desktop shortcut.

The installer includes its own local server environment. XAMPP is not required.

## Activate

1. NexTill displays a unique Installation ID.
2. Send that ID and your shop name to your NexTill supplier.
3. Enter the license key supplied for that installation.
4. Sign in using the credentials provided during setup or by your administrator.

License keys are installation-specific. Store the key securely and do not post it publicly.

## Configure Your Shop

After signing in:

1. Open **Settings → POS Settings**.
2. Configure currency, default discount, and sale-price markup.
3. Open **Settings → Receipt Settings**.
4. Enter the shop name, address, contact details, and receipt policy.
5. Add users, quantity units, variations, customers, and products.
6. Create a database backup before live trading.

## Thermal Printer

1. Install the printer manufacturer's Windows driver.
2. Select the correct paper width in the printer settings, normally 58 mm or 80 mm.
3. Set margins to the printer's minimum supported values.
4. Print a test invoice from NexTill.

NexTill fits the receipt to the printable width reported by the selected printer.

## Barcode Scanner

Most USB barcode scanners work as keyboard input:

1. Connect the scanner.
2. Open the POS screen.
3. Scan a product barcode.
4. Confirm that the scanner sends Enter after the barcode.

## Updates

Open **Dashboard → System Update**. NexTill will:

1. Check the signed release manifest.
2. Download the update.
3. Verify its SHA-256 hash and RSA signature.
4. Back up the database and changed application files.
5. Install migrations and application changes.
6. Preserve the database, license, settings, and existing backups.

Do not manually extract the OTA ZIP over an installation.

## Startup And Recovery

NexTill installs Apache and MariaDB as automatic Windows services. The NexTill shortcut also checks service health and starts or repairs services when required.

If NexTill does not open:

1. Restart Windows.
2. Run the NexTill shortcut as administrator once.
3. Check that another program is not using ports `8787` or `3307`.
4. Submit a support request with the exact error message.

## Uninstall

Use **Windows Settings → Apps → Installed apps → NexTill POS → Uninstall**.

Back up shop data before uninstalling. Uninstallation may remove the local application and database runtime.
