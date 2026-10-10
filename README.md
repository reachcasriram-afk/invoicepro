# InvoicePro — Offline CA Practice Billing & Collection System

A free, offline, single-file invoicing and receivables-management tool built for a small Chartered Accountant practice. No installation, no server, no account, no internet connection required after the page loads — all data is stored locally in your browser (IndexedDB).

Crafted by CA Sriram (A SRI RAM & ASSOCIATES) — reachcasriram@gmail.com

## Features

- Client Master, Service Master and Firm Settings
- GST-compliant invoices (CGST+SGST / IGST, auto-detected from client state)
- Client-specific saved fees and recurring engagements (monthly/quarterly/half-yearly/annual) with one-click invoice generation
- Optional payment due dates — no forced deadlines
- Collections Centre with receivable ageing (0-30 / 31-60 / 61-90 / 90+ days)
- Client Ledger (billed, received, outstanding, full transaction history)
- Payment recording with multiple transactions per invoice
- WhatsApp and Email (Gmail) payment reminders — pre-filled, never sent automatically
- Reports: Billing, Collections, Outstanding (CSV export)
- Global search, keyboard shortcuts
- Backup & restore (JSON), with staleness warning and safety backup before restore
- PDF and Word (.docx) invoice export, printable layout

## How to use

Open **[index.html](index.html)** in any modern browser (Chrome, Edge, Firefox). That's it — no setup.

> ⚠️ Your data is stored in your browser's local storage (IndexedDB), tied to this exact page/origin. **Take regular backups** (Settings → Data → Backup) and keep the backup file safe — clearing browser data will erase your invoices if you have no backup.

## License

Copyright © 2026 CA Sriram, A SRI RAM & ASSOCIATES. All rights reserved.

You are free to use this app in your own practice. Selling, redistributing, hosting elsewhere or modifying it for others requires written consent from the author. See [LICENSE](LICENSE) for the full terms.

GST rates, SAC codes and invoice numbering are configured by you and are provided as drafting aids only — review the figures for each invoice and apply your own professional judgment before issuing it.
