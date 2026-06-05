# Functional Test Cases — Logout

| Test Case ID | Requirement | Preconditions | Steps | Expected Result |
|---|---|---|---|---|
| TC-LOGOUT-01 | FR-19 | User is logged in | Open side menu. | Logout option is displayed. |
| TC-LOGOUT-02 | FR-19, FR-20 | User is logged in | Click Logout. | User is redirected to login page. |
| TC-LOGOUT-03 | FR-20 | User is logged out | Click browser Back button. | Authenticated session is not restored. |
| TC-LOGOUT-04 | FR-20 | User is logged out | Open product catalogue URL directly. | Access is blocked or user is redirected to login page. |