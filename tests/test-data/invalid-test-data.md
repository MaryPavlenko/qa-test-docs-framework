# Invalid Test Data

## Overview

This document contains invalid test data used for negative testing scenarios in Swag Labs.

The data below is expected to trigger validation errors, access restrictions or unsuccessful user actions.

---

# Invalid Login Test Data

| Field | Invalid Value | Expected Result |
|---|---|---|
| Username | "" | Validation error |
| Username | invalid_user | Login failure |
| Username | admin | Login failure |
| Username | standard_user! | Login failure |
| Username | 123456 | Login failure |
| Password | "" | Validation error |
| Password | wrong_password | Login failure |
| Password | SECRET_SAUCE | Login failure |
| Password | secret sauce | Login failure |

---

# Restricted User Data

| Field | Value | Expected Result |
|---|---|---|
| Username | locked_out_user | User cannot log in |
| Password | secret_sauce | Access denied error |

---

# Invalid Checkout Test Data

| Field | Invalid Value | Expected Result |
|---|---|---|
| First Name | "" | Validation error |
| Last Name | "" | Validation error |
| Postal Code | "" | Validation error |
| Postal Code | abc!!! | Validation error |
| Postal Code | @@@@ | Validation error |
| Postal Code | 123456789999999999 | Validation error |

---

# Special Character Test Data

| Field | Invalid Value |
|---|---|
| Username | <script>alert(1)</script> |
| First Name | !!!### |
| Last Name | 123456 |

---

# Notes

Invalid test data helps verify:

- input validation;
- error handling;
- restricted access behavior;
- system stability for unexpected input.