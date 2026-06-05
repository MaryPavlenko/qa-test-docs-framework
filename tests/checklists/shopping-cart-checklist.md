# Shopping Cart Checklist — Swag Labs

## Positive Checks

- [ ] Add one product to cart → Cart counter shows “1”
- [ ] Add multiple products to cart → Cart counter shows correct number of added products
- [ ] Open cart page → Added products are displayed
- [ ] Check product in cart → Product name, price and quantity are displayed
- [ ] Click “Remove” for product in cart → Product is removed from cart
- [ ] Remove one product from multiple products → Cart counter decreases by 1
- [ ] Remove all products from cart → Cart becomes empty and counter disappears
- [ ] Click “Continue Shopping” → User returns to product catalogue
- [ ] Click “Checkout” with products in cart → Checkout page is opened

## Negative / Edge Checks

- [ ] Open cart without adding products → Cart page is opened with no products
- [ ] Try to proceed to checkout with empty cart → Checkout is blocked or handled according to application logic
- [ ] Refresh cart page with products added → Cart state is preserved during active session
- [ ] Log out after adding products → Cart state is cleared or preserved according to application logic
- [ ] Navigate back from cart to catalogue → User remains logged in and cart state is preserved

## UI Checks

- [ ] Verify cart icon is visible on product catalogue page
- [ ] Verify cart counter is visible after adding product
- [ ] Verify cart counter is not displayed when cart is empty
- [ ] Verify Remove button is visible for each product in cart