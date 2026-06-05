# Decision Table Testing — Checkout Validation

## Objective

Verify checkout form validation using Decision Table Testing technique.

---

## Decision Table

| First Name | Last Name | Postal Code | Expected Result |
|---|---|---|---|
| Valid | Valid | Valid | Checkout success |
| Empty | Valid | Valid | Validation error |
| Valid | Empty | Valid | Validation error |
| Valid | Valid | Empty | Validation error |
| Empty | Empty | Empty | Validation error |

---

## Notes

Decision tables help validate business rules and input combinations efficiently.