# EarnPay prototype

Clickable prototype of EarnPay, an earned-wage-access product: employees draw part of the wages they have already earned before payday, and the amount is deducted automatically from their next payroll.

**Live demo:** https://eshimokhai-c.github.io/earnpay-prototype/

## What's in it

- **Employee app** – available balance, withdrawal with fee and VAT breakdown, approval and payout states, history.
- **Employer admin** – overview, approval queue, employees (add manually or sync from an HR system), attendance register (edit or sync from a time system), payroll deductions, reports with CSV export, and settings.

All data is fictional and lives in the browser (`localStorage`). Use **Reset demo** in the top bar to start fresh.

It is a single static file (`index.html`) with no build step.
