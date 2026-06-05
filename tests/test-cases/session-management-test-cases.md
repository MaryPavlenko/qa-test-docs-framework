# Functional Test Cases — Session Management

| Test Case ID | Requirement | Preconditions | Steps | Expected Result |
|---|---|---|---|---|
| TC-SESSION-01 | FR-01 | User is logged in | Refresh product catalogue page. | User remains logged in. |
| TC-SESSION-02 | FR-20 | User is logged out | Refresh login page. | Login page remains displayed. |
| TC-SESSION-03 | FR-20 | User is logged out | Try to open cart page directly. | Access is blocked or user is redirected to login page. |
| TC-SESSION-04 | FR-08, FR-09 | User is logged in; product added to cart | Refresh page. | Cart state is preserved during active session. |
| TC-SESSION-05 | FR-20 | User logs out after adding product to cart | Log in again. | Cart state behaves according to application logic. |