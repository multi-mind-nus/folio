# Synthetic sample files

These synthetic benchmark documents make the Folio upload and review flow easy to demonstrate. The files cover both PDF and JPEG input. Create or select the **matching client and period** before uploading; otherwise, an entity or period mismatch is expected.

| Folder | Demo client and period | What to try |
| :--- | :--- | :--- |
| [`loan-reconciliation/`](loan-reconciliation/) | Redwood Imports Pte. Ltd. · November 2026 | Compare a bank debit with a correct and an incorrect loan statement. |
| [`expense-claim/`](expense-claim/) | Keystone Projects Solutions Pte. Ltd. · November 2026 | Review a bank payment, a multilingual expense claim, and three receipts. |

## Loan repayment

Create a November 2026 request with **bank statement** and **loan statement** requirements for Redwood Imports Pte. Ltd. Upload `bank_2026_11.pdf` and `wrong_loan_statement.pdf`, confirm their placement, and submit. The bank shows a **SGD 6,992.98** loan payment, while the incorrect statement totals **SGD 7,500.52**. Inspect the review or any follow-up, then add `loan_statement.pdf` in the next round. Its principal **SGD 6,030.91** plus interest **SGD 962.07** equals the bank debit.

## Employee expense claim

Create a November 2026 request for Keystone Projects Solutions Pte. Ltd. with **bank statement**, **employee expense claim**, and **receipt** requirements. Upload `bank_2026_11.jpg`, `expense_claim.pdf`, and `receipt_1.jpg` through `receipt_3.jpg`; confirm the placement and submit. The claim and bank payment are **SGD 341.20**. The three receipts total **SGD 254.14 + 19.57 + 67.49 = 341.20**. `partial_expense_claim.pdf` is an alternative incomplete claim for a separate run, not an additional document to submit with the complete claim.

Classification places uploaded files into requirements; the deeper evidence review begins only after **Submit**. AI outcomes are proposals subject to backend validation and accountant confirmation.
