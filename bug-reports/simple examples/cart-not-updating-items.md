# Bug Report: Shopping Cart Does Not Update Correctly

## Bug ID
BR_CART_001

## Title
Shopping cart does not update item quantity and total price correctly

---

## Environment
- Website type: E-commerce web application  
- Browser: Google Chrome  
- OS: Windows 10  
- Device: Desktop  
- Testing environment: Test / Staging  

---

## Preconditions
- User is on the product catalog page
- Product is available in stock
- User is not logged out
- Internet connection is stable

---

## Steps to Reproduce
1. Open the website
2. Select any product from the catalog
3. Click the **"Add to Cart"** button
4. Open the shopping cart
5. Change the quantity of the product
6. Refresh the page

---

## Actual Result
- Product quantity is not updated or resets to the previous value
- Total price is calculated incorrectly
- In some cases, the cart becomes empty after page refresh

---

## Expected Result
- Product quantity is updated correctly
- Total price is recalculated according to the selected quantity
- Cart data is saved correctly after page refresh

---

## Severity
Critical

---

## Priority
High

---

## Frequency
Always (100%)

---

## Attachments
- Console errors observed in DevTools
- Network tab shows incorrect backend responses (4xx / 5xx)
- Screenshots and logs (if available)

---

## Root Cause (Assumption)
Incorrect database relationship configuration caused improper synchronization between cart data and backend logic, resulting in data loss and incorrect cart behavior.

---

## Notes
The issue directly affects the checkout flow and prevents users from completing purchases, leading to potential revenue loss and poor user experience.
