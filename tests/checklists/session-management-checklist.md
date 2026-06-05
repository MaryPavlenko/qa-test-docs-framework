# Session Management Checklist — Swag Labs

## Login Session

- [ ] Log in with valid credentials → User session is created
- [ ] Refresh product catalogue page after login → User remains logged in
- [ ] Open cart page after login → User remains logged in
- [ ] Open checkout page after login with product in cart → User remains logged in

## Unauthorized Access

- [ ] Open product catalogue URL without login → Access is blocked or user is redirected to login page
- [ ] Open cart URL without login → Access is blocked or user is redirected to login page
- [ ] Open checkout URL without login → Access is blocked or user is redirected to login page

## Logout Session

- [ ] Log out from active session → User session is ended
- [ ] After logout, refresh page → Login page remains displayed
- [ ] After logout, use browser Back button → Authenticated session is not restored
- [ ] After logout, open protected URL directly → Access is blocked or user is redirected to login page

## Cart State During Session

- [ ] Add product to cart and refresh page → Cart state is preserved during active session
- [ ] Add product to cart and navigate between pages → Cart state is preserved during active session
- [ ] Log out with product in cart → Cart state is cleared or preserved according to application logic
- [ ] Log in again after logout → Cart state behaves according to application logic