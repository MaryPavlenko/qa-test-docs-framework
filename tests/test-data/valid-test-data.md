# Valid Test Data

## Overview

This document contains valid test data used for positive testing scenarios in Swag Labs.

The data below is expected to be accepted by the system and allow successful user actions.

---

# Login Test Data

| Field | Valid Value | Description |
|---|---|---|
| Username | standard_user | Standard valid user |
| Username | problem_user | User with predefined application issues |
| Username | performance_glitch_user | User with performance-related delays |
| Username | error_user | User for error simulation scenarios |
| Username | visual_user | User for visual testing scenarios |
| Password | secret_sauce | Valid password for all test users |

---

# Checkout Test Data

| Field | Valid Value |
|---|---|
| First Name | Mary |
| Last Name | Pavlenko |
| Postal Code | 12345 |
| Postal Code | SW1A1AA |
| Postal Code | EC1A1BB |

---

# Product Test Data

| Field | Valid Value |
|---|---|
| Product Name | Sauce Labs Backpack |
| Product Name | Sauce Labs Bolt T-Shirt |
| Product Name | Sauce Labs Bike Light |

---

# Notes

- All accepted usernames are provided by the Swag Labs demo application.
- The password `secret_sauce` is valid for all available users except restricted scenarios such as `locked_out_user`.