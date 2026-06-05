# Boundary Value Analysis — Postal Code

## Objective

Verify postal code validation using Boundary Value Analysis technique.

---

## Boundary Test Data

| Scenario | Input Value | Expected Result |
|---|---|---|
| Empty value | "" | Validation error |
| Minimum length | 1 | Validation handling |
| Typical valid value | 12345 | Accepted |
| Maximum expected length | 9999999999 | Accepted or validation handling |
| Above maximum length | 12345678901234567890 | Validation error |

---

## Notes

Boundary Value Analysis focuses on edge cases near minimum and maximum input limits.