# Error Validation Checklist — Swag Labs

## Login Validation

- [ ] Click Login with empty username and password → Error message is displayed
- [ ] Click Login with empty username and valid password → Error message is displayed
- [ ] Click Login with valid username and empty password → Error message is displayed
- [ ] Enter invalid username and valid password → Error message is displayed
- [ ] Enter valid username and invalid password → Error message is displayed
- [ ] Log in as locked-out user → Access is blocked and error message is displayed

## Checkout Form Validation

- [ ] Click Continue with all checkout fields empty → Validation error is displayed
- [ ] Leave First Name empty → Validation error is displayed
- [ ] Leave Last Name empty → Validation error is displayed
- [ ] Leave Postal Code empty → Validation error is displayed
- [ ] Enter spaces only in required fields → Validation error is displayed or spaces are not accepted
- [ ] Enter very long values in required fields → System handles input correctly
- [ ] Enter special characters in required fields → System handles input according to validation rules

## Error Message UI

- [ ] Verify error message is visible
- [ ] Verify error message text is clear and readable
- [ ] Verify error message is displayed near the related form
- [ ] Verify error state is visually highlighted
- [ ] Verify user can correct input after validation error
- [ ] Verify error message disappears after valid input is submitted