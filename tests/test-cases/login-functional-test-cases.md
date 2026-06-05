# Functional Test Cases — Login

| Test Case ID | Requirement | Preconditions | Steps | Expected Result |
|---|---|---|---|---|
| TC-LOGIN-01 | FR-01 | User is on login page | Enter valid username and password. Click Login. | User is redirected to product catalogue. |
| TC-LOGIN-02 | FR-02 | User is on login page | Enter invalid username and valid password. Click Login. | Error message is displayed. |
| TC-LOGIN-03 | FR-02 | User is on login page | Enter valid username and invalid password. Click Login. | Error message is displayed. |
| TC-LOGIN-04 | FR-03 | User is on login page | Leave both fields empty. Click Login. | Error message is displayed. |
| TC-LOGIN-05 | FR-03 | User is on login page | Enter username only. Click Login. | Error message is displayed. |
| TC-LOGIN-06 | FR-04 | User is on login page | Log in as locked_out_user. | Access is blocked and error message is displayed. |