# Financial Audit & Reconciliation Data Pipeline

## Objective
Automates internal control exception flagging across subledger transaction data using Python (`pandas`).

## Key Checks
- **Duplicate Invoice Detection:** Flags repeated invoice IDs to prevent double payments.
- **Missing Primary Keys:** Identifies unmapped subledger transactions or missing document numbers.
- **Negative Variance Isolation:** Spotlights credit memos, reversals, or posting errors.
