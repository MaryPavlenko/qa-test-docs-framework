# Logout Flow Checklist — Swag Labs

## Positive Checks

- [ ] Log in with valid credentials → Product catalogue page is displayed
- [ ] Open side menu → Logout option is displayed
- [ ] Click “Logout” → User is redirected to the login page
- [ ] Log out from active session → User session is ended
- [ ] After logout, open product catalogue URL directly → Access is blocked or user is redirected to login page
- [ ] After logout, click browser Back button → Authenticated session is not restored
- [ ] After logout, refresh the page → Login page remains displayed

## Negative / Edge Checks

- [ ] Click “Logout” with slow internet connection → Logout action is completed or loading state is handled correctly
- [ ] Click “Logout” multiple times quickly → User is logged out once without duplicated actions
- [ ] Open logout flow with products in cart → Cart state is cleared or preserved according to application logic
- [ ] Log out and log in again → User can start a new session successfully

## UI Checks

- [ ] Verify side menu opens correctly
- [ ] Verify Logout option is visible and readable
- [ ] Verify Logout option is clickable
- [ ] Verify user is redirected to the correct page after logout