# Traceability Matrix

## Overview

This traceability matrix maps functional requirements to related test cases and QA artifacts.

The matrix helps ensure that all functional requirements are covered by testing activities.

---

| Requirement ID | Requirement Description | Related Test Cases | Related Checklist | Coverage Status |
|---|---|---|---|---|
| FR-01 | User can log in with valid credentials | login-functional-test-cases.md | login-page-checklist.md | Covered |
| FR-02 | Error message for invalid credentials | login-functional-test-cases.md | error-validation-checklist.md | Covered |
| FR-03 | Error message for empty login fields | login-functional-test-cases.md | error-validation-checklist.md | Covered |
| FR-04 | Locked-out user cannot log in | login-functional-test-cases.md | login-page-checklist.md | Covered |
| FR-05 | Product catalogue is displayed after login | product-catalog-test-cases.md | product-catalog-checklist.md | Covered |
| FR-06 | Product contains name, image, description and price | product-catalog-test-cases.md | product-catalog-checklist.md | Covered |
| FR-07 | User can sort products | product-catalog-test-cases.md | product-catalog-checklist.md | Covered |
| FR-08 | User can add products to cart | shopping-cart-test-cases.md | shopping-cart-checklist.md | Covered |
| FR-09 | Cart counter displays added products | shopping-cart-test-cases.md | shopping-cart-checklist.md | Covered |
| FR-10 | User can remove products from cart | shopping-cart-test-cases.md | shopping-cart-checklist.md | Covered |
| FR-11 | User can open cart page | shopping-cart-test-cases.md | shopping-cart-checklist.md | Covered |
| FR-12 | User can start checkout | checkout-flow-test-cases.md | checkout-flow-checklist.md | Covered |
| FR-13 | Checkout requires mandatory fields | checkout-flow-test-cases.md | error-validation-checklist.md | Covered |
| FR-14 | Validation errors are displayed | checkout-flow-test-cases.md | error-validation-checklist.md | Covered |
| FR-15 | Order overview is displayed | checkout-flow-test-cases.md | checkout-flow-checklist.md | Covered |
| FR-16 | User can complete checkout | checkout-flow-test-cases.md | checkout-flow-checklist.md | Covered |
| FR-17 | Success message after order completion | checkout-flow-test-cases.md | checkout-flow-checklist.md | Covered |
| FR-18 | User can return to catalogue | checkout-flow-test-cases.md | checkout-flow-checklist.md | Covered |
| FR-19 | User can log out | logout-test-cases.md | logout-flow-checklist.md | Covered |
| FR-20 | User is redirected after logout | logout-test-cases.md | session-management-checklist.md | Covered |