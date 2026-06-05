# Equivalence Partitioning — Login Validation

## Objective

Verify login validation using equivalence partitioning technique.

---

## Valid Partitions

| Input Type | Example | Expected Result |
|---|---|---|
| Valid username | standard_user | Login success |
| Valid password | secret_sauce | Login success |

---

## Invalid Partitions

| Input Type | Example | Expected Result |
|---|---|---|
| Invalid username | invalid_user | Login error |
| Invalid password | wrong_password | Login error |
| Empty username | "" | Validation error |
| Empty password | "" | Validation error |
| Locked user | locked_out_user | Access denied |

---

## Notes

Equivalence Partitioning helps reduce the total number of test cases while maintaining sufficient coverage.