# Functional Requirements (FR)
- (✅) **Create Transaction:** The user must be able to create a new transaction.
- (✅) **Account Summary:** The system must provide a summary (balance) of the user's account.
- (✅) **List Transactions:** The user can list all transactions that have occurred.
- (✅) **View Single Transaction:** The user can access the details of a specific transaction.

# Business Rules (BR)
- (✅) **Transaction Type:** Each transaction can be a credit (which adds to the total) or a debit (which subtracts from the total).
- (❌) **User Identification:** It is necessary to identify the user in every request, ensuring that actions and data are linked to them.
- (❌) **View Permission:** The user can only view the transactions they have created.
