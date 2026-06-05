# Functional Requirements — Swag Labs

## 1. Overview
Swag Labs is ae-commerce web application that allows users to log in, view products, add items to the cart, and complete the checkout flow.

## 2. User Roles
### Registered User

The application provides several predefined user accounts for testing purposes.

## 3. Functional Requirements
| ID | Area | Functional Requirement |
|---|---|---|
| FR-01 | Login | The system shall allow users to log in with a valid username and password. |
| FR-02 | Login | The system shall display an error message when username or password is invalid. |
| FR-03 | Login | The system shall display an error message when username or password is empty. |
| FR-04 | Login | The system shall not allow locked-out users to access the product page. |
| FR-05 | Product Catalogue | The system shall display a list of available products after successful login. |
| FR-06 | Product Catalogue | Each product shall have a name, image, description and price. |
| FR-07 | Product Catalogue | The user shall be able to sort products by name and price. |
| FR-08 | Shopping Cart | The user shall be able to add products to the shopping cart. |
| FR-09 | Shopping Cart | The cart icon shall display the number of added products. |
| FR-10 | Shopping Cart | The user shall be able to remove products from the cart. |
| FR-11 | Shopping Cart | The user shall be able to open the cart page and view selected products. |
| FR-12 | Checkout | The user shall be able to start checkout from the cart page. |
| FR-13 | Checkout | The system shall require First Name, Last Name and Postal Code. |
| FR-14 | Checkout | The system shall display validation errors if required checkout fields are empty. |
| FR-15 | Checkout | The system shall display an order overview before purchase confirmation. |
| FR-16 | Checkout | The system shall allow the user to complete the order. |
| FR-17 | Order Completion | The system shall display a success message after the order is completed. |
| FR-18 | Order Completion | The user shall be able to return to the product catalogue after completing the order. |
| FR-19 | Logout | The user shall be able to open the menu and log out. |
| FR-20 | Logout | After logout, the system shall return the user to the login page. |

## 4. Test Scope
The testing scope includes:
- Login validation
- Product catalogue display
- Sorting functionality
- Add/remove items from cart
- Cart counter
- Checkout form validation
- Order completion flow
- Logout flow

## 5. Out of Scope
The following areas are out of scope:
- Real payment processing
- Real user registration
- Backend/database validation
- Email notifications
- Performance testing