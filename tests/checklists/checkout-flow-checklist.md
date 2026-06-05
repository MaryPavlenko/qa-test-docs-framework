# Checkout Flow Checklist — Swag Labs

## Positive Checks

- [ ] Add product to cart and click “Checkout” → Checkout form is displayed
- [ ] Fill First Name, Last Name and Postal Code with valid data → User can continue checkout
- [ ] Click “Continue” with valid checkout data → Order overview page is displayed
- [ ] Check order overview → Selected products, prices, tax and total are displayed
- [ ] Click “Finish” on order overview page → Order is completed
- [ ] Complete order successfully → Success message is displayed
- [ ] Click “Back Home” after order completion → User returns to product catalogue

## Negative Checks

- [ ] Leave all checkout fields empty and click “Continue” → Validation error is displayed
- [ ] Leave First Name empty → Validation error for First Name is displayed
- [ ] Leave Last Name empty → Validation error for Last Name is displayed
- [ ] Leave Postal Code empty → Validation error for Postal Code is displayed
- [ ] Enter only spaces into required fields → Validation error is displayed or spaces are not accepted
- [ ] Click “Cancel” on checkout form → User returns to cart page
- [ ] Click “Cancel” on order overview page → User returns to product catalogue / previous flow according to application logic

## Edge Checks

- [ ] Refresh checkout form page → Checkout state is handled correctly
- [ ] Refresh order overview page → Order data remains correct or user is redirected according to application logic
- [ ] Remove product before checkout → Removed product is not displayed in order overview
- [ ] Try to complete checkout twice → Duplicate order is not created

## UI Checks

- [ ] Verify First Name field is visible
- [ ] Verify Last Name field is visible
- [ ] Verify Postal Code field is visible
- [ ] Verify Continue button is visible
- [ ] Verify validation messages are readable
- [ ] Verify success message is displayed clearly after order completion