# YK Eggs Invoice Studio PWA

A static, installable invoice generator designed for GitHub Pages and iPhone. No backend, account, or subscription is required.

## Features
- Create invoices with customer details, multiple line items, discounts, amount paid, balance and payment status.
- Automatically calculate totals in UGX.
- Save, view, edit, search, print and delete invoices.
- Generate a PDF locally, then share it with WhatsApp, Mail, AirDrop or other supported iPhone apps. On browsers that do not support file sharing, the PDF downloads and can be shared from Files.
- IndexedDB local storage; invoices remain in the browser on that device.
- Export and restore a JSON backup.
- Offline app shell after the first successful load.

## Publish with GitHub Pages
1. Extract the ZIP.
2. Open your GitHub repository for YK Eggs.
3. Upload the contents of this folder (not the enclosing folder) to the repository root. Keep `index.html`, `app.js`, `styles.css`, `manifest.webmanifest`, `sw.js`, `README.md`, and `assets/` together.
4. Commit the changes.
5. In **Settings → Pages**, select **Deploy from a branch**, choose your main branch and `/ (root)`, then Save.
6. Wait for GitHub Pages to finish publishing, then open your Pages URL over HTTPS.

## Install on iPhone
1. Open the published HTTPS URL in Safari.
2. Tap the Share icon.
3. Choose **Add to Home Screen**.
4. Tap **Add**. Launch YK Eggs from the new Home Screen icon.

## Local data and backups
Invoices are stored in IndexedDB for this browser profile on this device. Clearing Safari website data, deleting the app/site data, or changing browser profiles can remove local invoices. Use **Invoice history → Backup** regularly and store the JSON backup somewhere safe. Restore it with the Restore button.

## PDF sharing
Use **PDF / Share** on an invoice. On supported iPhones, the native share sheet opens with the PDF attached; choose WhatsApp, Mail, AirDrop, etc. If direct file sharing is unavailable, the PDF downloads and can be attached from the Files app.

## Important
- GitHub Pages serves the app but does not store invoice data. Each device/browser has its own local records; there is no automatic sync between devices.
- For privacy, use a device passcode and keep backup files secure.
