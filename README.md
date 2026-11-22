# BlackFrame Books

Free, private bookkeeping for small businesses in Nigeria. One file (`index.html`), no sign-up, no server, no build step.

## What it does
- Double-entry ledger underneath; money is stored as whole kobo; posted entries are never edited, only reversed
- Invoices (one-off, monthly, yearly) in naira or US dollars, with VAT and withholding tax (WHT)
- Receipts, and PDF / PNG / JPG export of invoices, receipts and reports
- Client money held for others is kept out of your revenue, with a payout button
- Notification bell: overdue and due-soon invoices, recurring invoices ready, client money held, VAT and WHT reminders
- Analytics (this month, 3, 6 or 12 months), profit and loss, balance sheet, trial balance, and statements for one client, channel or expense type
- Your own business name or logo on every invoice and receipt

## Privacy
Everything is saved in your browser on your device. Nothing is sent to any server, and there are no accounts, analytics or tracking.
Fonts and two libraries (html2canvas, jsPDF) load from public CDNs, so the page needs an internet connection.
Clearing your browser data erases your books. Use **Settings > Download backup** regularly. You can restore a backup or erase everything from the same page.

## Use it
Open the hosted page, then **Settings** to enter your business details. Or press **Try with sample data** on the first screen to explore.

## Host your own copy (GitHub Pages)
1. Push this repository to GitHub.
2. Repository **Settings > Pages > Build and deployment**: deploy from branch `main`, folder `/ (root)`.
3. Your app appears at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Limits
- Built for Nigerian businesses: the books are kept in naira (₦). Invoices can be in USD, recorded at the exchange rate you enter when paid.
- Data does not sync between devices. Use backup and restore to move it.
- Not accounting, legal or tax advice. Confirm VAT and WHT rates, and when they apply to you, with a qualified accountant.
