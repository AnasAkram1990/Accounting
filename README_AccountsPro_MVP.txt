# AccountsPro Bookkeeping MVP

## Included in this prototype
- Multiple client workspaces in one browser
- Starter chart of accounts
- Double-entry journal and receipt/payment vouchers with debit-credit validation
- General ledger and trial balance
- Profit & loss and balance sheet
- Basic FBR/SRB/withholding tax tracking register
- CSV export for vouchers, ledger, trial balance, financial statements and tax register
- Printable voucher layout
- Basic NGO/NPO project or cost-centre tagging

## Run it
Open `accountspro_bookkeeping_mvp.html` in a modern desktop browser. Demo records are included.
Data is stored in the browser's local storage on that device/browser. Use only sample data.

## Important limitations
This is a front-end MVP/demo, not a deployed cloud service. It does not yet provide secure user login, server-side database storage, multi-user collaboration, audit logs, approval workflows, encrypted backups, Excel `.xlsx` import, payroll processing, fixed-asset/depreciation schedules, invoice management, or automated/statutory FBR/SRB return filing. Tax rates and legal calculations must be verified against current legislation before production use.

## Production cloud version — recommended next phase
- Frontend: React/Next.js
- Backend API: authenticated server-side application
- Database: PostgreSQL with strict tenant/client-level data isolation
- Security: role-based access, MFA option, audit trail, TLS, encryption, scheduled backups and restore testing
- Accounting controls: immutable posted vouchers, reversals instead of deletion, period locks, approval workflow and reporting-date filters
- Add `.xlsx` import/export, invoice templates, payroll, fixed assets, project/grant reporting and configurable tax rules
- Deploy to a managed hosting provider with a production database and domain

Do not upload real client financial information until the cloud deployment and security controls are implemented and tested.
