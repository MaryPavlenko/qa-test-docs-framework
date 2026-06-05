# Boundary Value Analysis

## What is Boundary Value Analysis?

Boundary Value Analysis (BVA) is a test design technique focused on validating values at the edges of input ranges.
Defects are more likely to appear near boundary values, which is why testing minimum, maximum and neighboring values is important.

---

# When to use it
Boundary Value Analysis is useful for testing:
- input field length;
- numeric ranges;
- quantity limits;
- price ranges;
- password length;
- character restrictions;
- date ranges.

---

# Example from Swag Labs

## Feature

Checkout form — Postal Code field.

## Assumption

For this example, we assume that:

> Postal Code must contain from 5 to 10 characters.

---

# Boundary Values

| Boundary Type | Value | Expected Result |
|---|---|---|
| Below minimum | 4 characters | Validation error |
| Minimum value | 5 characters | Accepted |
| Minimum + 1 | 6 characters | Accepted |
| Maximum - 1 | 9 characters | Accepted |
| Maximum value | 10 characters | Accepted |
| Above maximum | 11 characters | Validation error |

---

## Example from Swag Labs
### Feature
Checkout form — Postal Code field.

### Requirement
The system shall require the user to enter a postal code during checkout.
For this example, we assume the following rule:
> Postal Code must contain from 5 to 10 characters.

## Boundary values
| Boundary | Test Value | Expected Result |
|---|---:|---|
| Below minimum | 4 characters | Validation error |
| Minimum value | 5 characters | Accepted |
| Minimum + 1 | 6 characters | Accepted |
| Maximum - 1 | 9 characters | Accepted |
| Maximum value | 10 characters | Accepted |
| Above maximum | 11 characters | Validation error |

## Test Data
| Test Case ID | Input Value | Type | Expected Result |
|---|---|---|---|
| BVA-01 | 1234 | Invalid | Error message is displayed |
| BVA-02 | 12345 | Valid | Postal code is accepted |
| BVA-03 | 123456 | Valid | Postal code is accepted |
| BVA-04 | 123456789 | Valid | Postal code is accepted |
| BVA-05 | 1234567890 | Valid | Postal code is accepted |
| BVA-06 | 12345678901 | Invalid | Error message is displayed |
