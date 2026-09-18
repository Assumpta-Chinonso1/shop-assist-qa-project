# Shop Assist – Test Scenarios

## Project Overview

This document contains the high-level test scenarios planned for the Shop Assist e-commerce platform.

The scenarios cover the major functional areas of the application and will later be converted into detailed test cases for execution.

---

## 1. Homepage

- TS-HOME-001 — Verify that the Shop Assist homepage loads successfully.
- TS-HOME-002 — Verify that the main homepage content is displayed correctly.
- TS-HOME-003 — Verify that the homepage navigation options are accessible.

## 2. Header & Navigation

- TS-NAV-001 — Verify that the Shop Assist logo is displayed.
- TS-NAV-002 — Verify that clicking the Shop Assist logo navigates to the homepage.
- TS-NAV-003 — Verify that the Home navigation option is accessible.
- TS-NAV-004 — Verify that the location/address selector is accessible from the header.
- TS-NAV-005 — Verify that the Login option is accessible from the header.
- TS-NAV-006 — Verify that the Sign Up option is accessible from the header.

## 3. Location / Address Selection

- TS-LOC-001 — Verify that the location/address selector opens when clicked.
- TS-LOC-002 — Verify that the address search field is displayed.
- TS-LOC-003 — Verify that a user can search for a delivery address.
- TS-LOC-004 — Verify that the "Use current location" option is available.
- TS-LOC-005 — Verify that the location selector can be closed.
- TS-LOC-006 — Verify that a selected delivery address is displayed correctly.
- TS-LOC-007 — Verify that the location selector is displayed correctly on different screen sizes.

## 4. Stores

- TS-STORE-001 — Verify that available stores are displayed on the website.
- TS-STORE-002 — Verify that store information is displayed correctly.
- TS-STORE-003 — Verify that the store availability status is displayed correctly.
- TS-STORE-004 — Verify that a user can select a store.
- TS-STORE-005 — Verify that the selected store displays its available products.
- TS-STORE-006 — Verify that a closed store cannot be selected for shopping, if applicable.
- TS-STORE-007 — Verify that clicking "View All" navigates the user to the complete Shops/Stores listing page.

## 5. Products

- TS-PROD-001 — Verify that products are displayed when a store is selected.
- TS-PROD-002 — Verify that product names are displayed correctly.
- TS-PROD-003 — Verify that product images are displayed correctly.
- TS-PROD-004 — Verify that product prices are displayed correctly.
- TS-PROD-005 — Verify that a user can select a product to view its details.
- TS-PROD-006 — Verify that product availability or stock status is displayed correctly.
- TS-PROD-007 — Verify that a user can add an available product to the cart.
- TS-PROD-008 — Verify that product information is displayed correctly on different screen sizes.

## 6. Search Shops

- TS-SEARCH-001 — Verify that the Search Shops field is displayed and accessible.
- TS-SEARCH-002 — Verify that a user can search for a store using a valid store name.
- TS-SEARCH-003 — Verify that the correct matching store is displayed for a valid search term.
- TS-SEARCH-004 — Verify that an appropriate response is displayed when no matching store is found.
- TS-SEARCH-005 — Verify that the user can clear the search term.
- TS-SEARCH-006 — Verify that store search works correctly on the dedicated Shops page.
- TS-SEARCH-007 — Verify that store search displays correctly on different screen sizes.

## 7. Cart

- TS-CART-001 — Verify that a user can open the cart.
- TS-CART-002 — Verify that an added product is displayed in the cart.
- TS-CART-003 — Verify that the product quantity can be increased or decreased in the cart.
- TS-CART-004 — Verify that a product can be removed from the cart.
- TS-CART-005 — Verify that the cart total is calculated correctly.
- TS-CART-006 — Verify that a user can proceed from the cart to checkout.

## 8. Login

- TS-LOGIN-001 — Verify that the Login feature is accessible.
- TS-LOGIN-002 — Verify that a user can log in with valid credentials.
- TS-LOGIN-003 — Verify that a user cannot log in with invalid credentials.
- TS-LOGIN-004 — Verify that required login fields are validated when left empty.
- TS-LOGIN-005 — Verify that an appropriate error message is displayed when login fails.
- TS-LOGIN-006 — Verify that a successfully logged-in user is redirected to the appropriate page.

## 9. Sign Up

- TS-SIGNUP-001 — Verify that the Sign Up feature is accessible.
- TS-SIGNUP-002 — Verify that a new user can create an account with valid registration information.
- TS-SIGNUP-003 — Verify that a user cannot create an account with invalid registration information.
- TS-SIGNUP-004 — Verify that required registration fields are validated when left empty.
- TS-SIGNUP-005 — Verify that appropriate validation or error messages are displayed when registration fails.
- TS-SIGNUP-006 — Verify that a successfully registered user is redirected to the appropriate page.

## 10. Checkout

- TS-CHECKOUT-001 — Verify that a user can proceed from the cart to the checkout page.
- TS-CHECKOUT-002 — Verify that the checkout page displays the correct order information.
- TS-CHECKOUT-003 — Verify that the selected products, quantities, and prices are displayed correctly at checkout.
- TS-CHECKOUT-004 — Verify that the required delivery information can be provided or selected.
- TS-CHECKOUT-005 — Verify that the order total is calculated correctly at checkout.
- TS-CHECKOUT-006 — Verify that a user can proceed from checkout to payment.
- TS-CHECKOUT-007 — Verify that required checkout information is validated when left incomplete.

## 11. Delivery

- TS-DELIVERY-001 — Verify that the selected delivery address is displayed correctly during the delivery process.
- TS-DELIVERY-002 — Verify that available delivery options are displayed correctly.
- TS-DELIVERY-003 — Verify that the applicable delivery fee is displayed correctly.
- TS-DELIVERY-004 — Verify that the user can select an available delivery option.
- TS-DELIVERY-005 — Verify that the selected delivery option is reflected correctly in the order summary.
- TS-DELIVERY-006 — Verify that the user cannot continue with the order when required delivery information is incomplete.
- TS-DELIVERY-007 — Verify that delivery information is displayed correctly on different screen sizes.

## 12. Payment

- TS-PAY-001 — Verify that the available payment methods are displayed correctly.
- TS-PAY-002 — Verify that a user can select an available payment method.
- TS-PAY-003 — Verify that the selected payment method is reflected correctly in the order summary.
- TS-PAY-004 — Verify that a user can proceed with payment using valid payment information.
- TS-PAY-005 — Verify that payment is unsuccessful when invalid payment information is provided.
- TS-PAY-006 — Verify that an appropriate message is displayed when payment fails.
- TS-PAY-007 — Verify that the user receives appropriate confirmation after a successful payment.

## 13. Orders

- TS-ORDER-001 — Verify that a logged-in user can access the Orders section.
- TS-ORDER-002 — Verify that completed or previous orders are displayed correctly.
- TS-ORDER-003 — Verify that the order information displayed is correct.
- TS-ORDER-004 — Verify that a user can select an order to view its details.
- TS-ORDER-005 — Verify that the order status is displayed correctly.
- TS-ORDER-006 — Verify that the order total is displayed correctly.
- TS-ORDER-007 — Verify that the date and time of the order are displayed correctly.

## 14. Order Tracking

- TS-TRACK-001 — Verify that a user can access the tracking information for an active order.
- TS-TRACK-002 — Verify that the current status of an active order is displayed correctly.
- TS-TRACK-003 — Verify that the order tracking information reflects the actual progress of the order.
- TS-TRACK-004 — Verify that the estimated delivery information is displayed correctly, if available.
- TS-TRACK-005 — Verify that the tracking information is updated when the order status changes.
- TS-TRACK-006 — Verify that the tracking information is displayed correctly on different screen sizes.

## 15. FAQ

- TS-FAQ-001 — Verify that the FAQ section is displayed and accessible.
- TS-FAQ-002 — Verify that FAQ categories are displayed correctly.
- TS-FAQ-003 — Verify that FAQ questions are displayed under the appropriate categories.
- TS-FAQ-004 — Verify that clicking an FAQ question displays the corresponding answer.
- TS-FAQ-005 — Verify that an opened FAQ answer can be collapsed.
- TS-FAQ-006 — Verify that selecting an FAQ category displays the relevant questions.
- TS-FAQ-007 — Verify that the FAQ section displays correctly on different screen sizes.

## 16. Contact Support

- TS-SUPPORT-001 — Verify that the Contact Support option is displayed and accessible.
- TS-SUPPORT-002 — Verify that clicking Contact Support opens the appropriate support channel or page.
- TS-SUPPORT-003 — Verify that the available support contact information is displayed correctly.
- TS-SUPPORT-004 — Verify that a user can initiate a support request, if a support form or request option is available.
- TS-SUPPORT-005 — Verify that required fields are validated when a support form is submitted with incomplete information, if applicable.
- TS-SUPPORT-006 — Verify that appropriate confirmation or error feedback is displayed after submitting a support request, if applicable.
- TS-SUPPORT-007 — Verify that the Contact Support section displays correctly on different screen sizes.

## 17. App Download

- TS-APP-001 — Verify that the app download section is displayed and accessible.
- TS-APP-002 — Verify that the App Store download option is displayed and accessible.
- TS-APP-003 — Verify that the Google Play download option is displayed and accessible.
- TS-APP-004 — Verify that clicking the App Store option navigates to the appropriate destination.
- TS-APP-005 — Verify that clicking the Google Play option navigates to the appropriate destination.
- TS-APP-006 — Verify that the QR code is displayed correctly.
- TS-APP-007 — Verify that the app download section displays correctly on different screen sizes.

## 18. Footer

- TS-FOOTER-001 — Verify that the footer is displayed correctly on the website.
- TS-FOOTER-002 — Verify that the footer sections and information are displayed correctly.
- TS-FOOTER-003 — Verify that the links available in the footer are accessible.
- TS-FOOTER-004 — Verify that clicking a footer link navigates to the correct destination.
- TS-FOOTER-005 — Verify that external links in the footer, if available, open the appropriate destination.
- TS-FOOTER-006 — Verify that the footer displays correctly on different screen sizes.

---

## Testing Tools

- Trello — Test planning and scenario organization
- Microsoft Excel — Test case documentation and test execution
- Jira — Defect tracking and management
- Postman — API testing
- Test Automation Framework — Automated testing
- GitHub — Project documentation and portfolio

## Project Status

**Status:** In Progress

The test scenarios have been planned. Detailed test cases, test execution, defect tracking, API testing, and test automation will be completed as the project progresses.
