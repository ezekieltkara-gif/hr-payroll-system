# Accountant HR Management App

A browser-based, accountant-only HR management app for employees, attendance, leave, payroll, notifications, exports, and PGK reporting.

## Run

Open `index.html` in a modern browser. The app stores its data locally in the browser using `localStorage`.

On first use, create the Accountant password. The password is stored as a SHA-256 hash. This client-side demo should be placed behind server-side authentication and HTTPS before production use.

## Included

- Single Accountant login; no Employee, Manager, or Admin roles
- Dashboard summaries for employees, attendance, pending leave, and PGK payroll totals
- Employee, attendance, leave, and payroll management
- Automatic Net Pay calculation (`Salary - Deductions`)
- CSV payroll export, printable PDF payslip workflow, and BSP-compatible bank-file CSV export
- Full JSON backup and restore
- Payroll deadline and pending-leave notifications only
