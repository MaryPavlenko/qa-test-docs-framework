# Boundary Test Data

## Overview

This document contains boundary and edge-case test data used for Boundary Value Analysis (BVA).

Boundary testing verifies how the application behaves with minimum, maximum and out-of-range input values.

---

# Username Boundary Data

| Scenario | Input Value | Expected Result |
|---|---|---|
| Empty value | "" | Validation error |
| Minimum length | a | Login failure |
| Typical valid value | standard_user | Login success |
| Long username | standard_user_standard_user_standard_user | Login failure or validation handling |

---

# Password Boundary Data

| Scenario | Input Value | Expected Result |
|---|---|---|
| Empty value | "" | Validation error |
| Minimum length | a | Login failure |
| Valid password | secret_sauce | Login success |
| Long password | secret_sauce_secret_sauce_secret_sauce | Login failure |

---

# Postal Code Boundary Data

| Scenario | Input Value | Expected Result |
|---|---|---|
| Empty value | "" | Validation error |
| Minimum numeric value | 1 | Validation handling |
| Typical valid value | 12345 | Accepted |
| Maximum expected length | 9999999999 | Validation handling |
| Overly long value | 12345678901234567890 | Validation error |

---

# Name Field Boundary Data

| Scenario | Input Value | Expected Result |
|---|---|---|
| Empty value | "" | Validation error |
| Single character | A | Accepted |
| Typical value | Mary | Accepted |
| Very long value | MaryMaryMaryMaryMaryMaryMary | Validation handling |

---

# Notes

Boundary testing focuses on:

- minimum values;
- maximum values;
- just below boundary;
- just above boundary;
- empty input;
- unusually large input values.