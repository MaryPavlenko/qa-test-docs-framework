# Functional Test Cases — Checkout Flow

| Test Case ID | Requirement | Preconditions | Steps | Expected Result |
|---|---|---|---|---|
| TC-CHK-01 | FR-12 | Product is added to cart | Open cart and click Checkout. | Checkout form is displayed. |
| TC-CHK-02 | FR-13 | User is on checkout form | Fill First Name, Last Name and Postal Code. Click Continue. | User proceeds to order overview. |
| TC-CHK-03 | FR-14 | User is on checkout form | Leave First Name empty. Click Continue. | Validation error is displayed. |
| TC-CHK-04 | FR-14 | User is on checkout form | Leave Last Name empty. Click Continue. | Validation error is displayed. |
| TC-CHK-05 | FR-14 | User is on checkout form | Leave Postal Code empty. Click Continue. | Validation error is displayed. |
| TC-CHK-06 | FR-15 | Checkout form is completed | Click Continue. | Order overview is displayed. |
| TC-CHK-07 | FR-16 | User is on order overview page | Click Finish. | Order is completed. |
| TC-CHK-08 | FR-17 | Order is completed | Check confirmation page. | Success message is displayed. |
| TC-CHK-09 | FR-18 | Order is completed | Click Back Home. | User returns to product catalogue. |