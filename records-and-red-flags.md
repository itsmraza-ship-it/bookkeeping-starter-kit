# Records & Red Flags

What to keep, how long to keep it, how to store it — and the habits that quietly cause the biggest problems at tax and audit time.

> **Disclaimer:** This document is general guidance for organising your records. It is not tax, legal, or accounting advice, and it is not a substitute for advice about your specific facts. Retention periods vary by record type, jurisdiction, and situation — confirm what applies to you with a qualified professional.

## What to keep

Keep the record that proves the transaction — not just the bank line.

### Income records
- Invoices issued and proof of payment
- Payment processor reports (Stripe, PayPal, etc.) and payout reports
- Sales / marketplace reports, contracts, and statements of work
- Bank deposit records

### Expense records
- Receipts and supplier invoices showing: date, vendor, amount, and what was bought
- For meals / travel: the business purpose and who attended, noted on the receipt or in your books
- Bills, subscription confirmations, and cancellation notices
- Mileage / travel logs if you claim vehicle or travel costs

### Business and tax records
- Formation documents, EIN letter (CP-575 / 147C), operating agreement, and state filings / annual reports
- Filed tax returns and all supporting schedules and workpapers
- Sales tax filings, payroll filings, and 1099 / contractor records (W-9, W-8BEN, W-8BEN-E) if applicable
- Loan agreements, leases, and major contracts
- Bank, credit card, and processor statements for every business account

### The rule of thumb
If it explains money in, money out, or a filing position — keep it, and keep it tied to the transaction it proves.

## How long to keep records

As general guidance, IRS record-retention is commonly described in ranges of **3 to 7 years depending on the type of record and the situation** — for example, employment tax records are generally kept at least 4 years, records supporting a return are generally kept until the period of limitations for that return expires (often 3 years from filing, longer in some cases such as substantial understatement, and with no limit for a fraudulent or unfiled return), and property records are kept until the period expires for the year you dispose of the property.

Practical, conservative approach used by many small businesses:

- **Tax returns and supporting records:** at least 7 years
- **Bank / card / processor statements:** at least 7 years
- **Formation, ownership, property, and loan documents:** for as long as they are relevant, plus at least 7 years after the related final return / closure
- **State records:** check your state's rules — they can differ from federal periods

When in doubt, keep it longer. Digital storage is cheap; recreating a missing record is not.

Source to check for current detail: the IRS guidance on "How long to keep records" at irs.gov.

## Digital storage that works

- **One system, named consistently.** Example structure:
  ```
  Records/
    2026/
      2026-11/
        Statements/
        Receipts/
        Invoices-Issued/
        Bills/
        Filings/
  ```
- **Name files so a stranger can find them:** `2026-11-04_Stripe_Payout-Report.pdf`, `2026-11-12_GoogleWorkspace_Receipt.pdf`
- **Capture at the moment of purchase.** Photograph paper receipts the same day — thermal receipts fade.
- **Back up in two places.** Primary cloud storage + a second backup (another cloud service or an offline drive). Test that you can open the backup.
- **Keep access controlled.** Financial records are sensitive — use account security / 2FA, and share a view-only folder with your bookkeeper / tax preparer rather than emailing files around.
- **Don't store the only copy inside your accounting app.** Export statements, reports, and receipts to your own folder monthly as part of the close (see `monthly-routine.md`).

## Red flags — fix these early

### 1. Commingling funds
Paying personal expenses from the business account (or business expenses personally, routinely and undocumented). It blurs the LLC's separation, wrecks the books, and creates painful questions at filing time.
**Fix:** separate accounts, business card for business only, and record owner money as Contributions / Draws.

### 2. Missing receipts
A bank line proves money moved; it does not prove what it was for or that it was a business expense.
**Fix:** receipt captured the same day, matched at monthly close, missing ones chased within the week.

### 3. Personal expenses in the business account
Occasional mistakes happen — a personal charge on the wrong card. Leaving it coded as a business expense is the problem.
**Fix:** recode it to Owner Draws promptly and note the correction.

### 4. Uncategorized buildup
Hundreds of transactions sitting in "Uncategorized" at year-end means nobody actually knows what the P&L says.
**Fix:** the weekly 15-minute habit, and a hard rule — Uncategorized is zero at every monthly close.

### 5. Ignoring state filings
Founders often remember the federal return and miss the state annual report / renewal, sales tax filing, or registered agent renewal — leading to penalties or an LLC that is no longer in good standing.
**Fix:** calendar every state deadline when you form, and check the list quarterly.

### 6. No tax reserve
Spending every payout as it lands and discovering the tax bill at filing time.
**Fix:** automatic set-aside to business savings on every payout, at a percentage agreed with your tax professional.

### 7. Processor payouts taken at face value
Recording the net payout as revenue hides both true revenue and processing fees, and sales totals won't match processor reports (e.g. a 1099-K where one applies).
**Fix:** record gross sales as income, processing fees as an expense, and reconcile payouts.

### 8. Contractor paperwork at year-end
Trying to collect W-9 / W-8 forms in January for work paid the previous year.
**Fix:** collect the form before the first payment, every time.

---

None of these require an accounting degree to fix. They require a routine — and that's exactly what this kit gives you: a clean chart (`chart-of-accounts.csv`), a close you repeat (`monthly-routine.md`), and records that hold up when someone asks.
