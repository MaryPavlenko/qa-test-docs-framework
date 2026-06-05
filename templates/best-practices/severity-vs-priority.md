# Severity vs Priority

## Overview

Severity and Priority are two important attributes used in defect reporting.

They help the team understand both:

- how serious the defect is;
- how urgently it should be fixed.

---

## Severity

Severity describes the impact of the defect on the system or user.

It answers the question:

> How badly does this issue affect the application?

| Severity | Description | Example |
|---|---|---|
| Critical | The application or core flow is blocked | User cannot log in |
| High | Major functionality is broken, but workaround may exist | Checkout cannot be completed |
| Medium | Functionality works incorrectly but does not fully block the user | Cart counter shows incorrect number |
| Low | Minor issue with limited impact | Text alignment issue or typo |

---

## Priority

Priority describes how soon the defect should be fixed.

It answers the question:

> How urgent is this issue for the business or release?

| Priority | Description | Example |
|---|---|---|
| High | Should be fixed as soon as possible | Payment flow is broken before release |
| Medium | Should be fixed in the current or upcoming sprint | Incorrect validation message |
| Low | Can be fixed later | Minor UI inconsistency |

---

## Key Difference

| Attribute | Focus |
|---|---|
| Severity | Technical or user impact |
| Priority | Business urgency |

---

## Examples

| Defect | Severity | Priority | Explanation |
|---|---|---|---|
| User cannot log in | Critical | High | Core access flow is blocked |
| Checkout total is calculated incorrectly | High | High | Directly affects purchase accuracy |
| Cart badge shows outdated number | Medium | Medium | User can continue, but information is misleading |
| Product image is slightly stretched | Low | Low | Visual issue with limited functional impact |
| Typo on product description | Low | Low | Minor content defect |
| Company logo is broken on homepage before launch | Low | High | Low functional impact, but high business visibility |

---

## Notes

Severity is usually proposed by QA based on impact.

Priority is often agreed with Product Owner, Project Manager or business stakeholders based on release goals and business value.