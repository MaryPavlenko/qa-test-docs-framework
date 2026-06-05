# Login Page Checklist — Swag Labs

## Positive Checks

- [ ] Open the login page → Login form is displayed
- [ ] Enter valid username and password → User is successfully logged in
- [ ] Click Login button with valid credentials → Product catalogue page is displayed
- [ ] Log in as `standard_user` → User has access to the product catalogue
- [ ] Enter password into the password field → Password characters are masked

## Negative Checks

- [ ] Leave username and password fields empty and click Login → Error message is displayed
- [ ] Enter valid username and empty password → Error message is displayed
- [ ] Enter empty username and valid password → Error message is displayed
- [ ] Enter invalid username and valid password → Error message is displayed
- [ ] Enter valid username and invalid password → Error message is displayed
- [ ] Log in as `locked_out_user` → User is not allowed to access the product catalogue
- [ ] Try to access product page without login → User is redirected to login page / access is blocked

## UI Checks

- [ ] Verify username field is visible
- [ ] Verify password field is visible
- [ ] Verify Login button is visible
- [ ] Verify error message is readable and displayed near the login form