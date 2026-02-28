### TC-01: Viewing the product profile
**Preconditions:** 
- User is logged in
- User is on main page  

**Type:** Functional

**Steps:**
1. Click on the product title in the product profile

**Expected Result:** User successfully navigates to the product page with detailed information about the product (size, material, color, manufacturer), price and product photo

### TC-02: Сhecking the filter
**Preconditions:** 
- User is logged in
- User is on main page  

**Type:** Functional

**Steps:**
1. Click filter button in the upper right corner
2. Select Price (low to high) filter from the drop-down list 
3. Click on the selected option from the list

**Expected Result:** Products are sorted by price in ascending order
First product price is less than or equal to the second product price

### TC-03: Add an item to the shopping cart
**Preconditions:** 
- User is logged in
- User is on main page  

**Type:** Functional

**Steps:**
1. Select any product from the product list
2. Click on the "Add to cart" button in the lower-right corner of the product card
3. Click on the cart icon button in the upper-right corner of the page

**Expected Result:** Cart page is displayed
Selected product name, price and quantity are shown
Cart counter equals 1

### TC-04: Return to the main page from product page 
**Preconditions:** 
- User is logged in
- User is on product page  

**Type:** Functional

**Steps:**
1.  Click on the "Back to products" in the upper left corner of the page

**Expected Result:** User successfully navigated to the main page

### TC-05: Return to the main page from cart page 
**Preconditions:** 
- User is logged in
- User is on cart page  

**Type:** Functional

**Steps:**
1.  Click on the "Continue Shopping" button at the bottom of the page

**Expected Result:** User successfully navigates to the product page with detailed information about the product (size, material, color, manufacturer), price and product photo

### TC-06: Checkout
**Preconditions:** 
- User is logged in
- User is on main page  

**Type:** Functional

**Steps:**
1. Select any product from the product list
2. Click on the "Add to cart" button in the lower-right corner of the product card
3. Click on the cart icon button in the upper-right corner of the page
4. Click on the "Checkout" button at the bottom of the page
5.  Enter your First name
6.  Enter your Last name
7.  Enter your Zip/Postal Code
8.  Click on the "Finish" button at the bottom of the page

**Expected Result:** User receives a message about a successful Checkout.

### TC-07: Removing a product from the shopping cart 
**Preconditions:** 
- User is logged in
- User is on cart page  

**Type:** Functional

**Steps:**
1.  Click on the "Remove" button at the bottom of the product card

**Expected Result:** User sees empty Cart

### TC-08: Checking button social media
**Preconditions:** 
- User is logged in
- User is on product page  

**Type:** Functional

**Steps:**
1.  Click on the "Facebook" button at the bottom of the product page

**Expected Result:** User goes to the Facebook page by opening a new tab

### TC-09: Access to the about page via the menu
**Preconditions:** 
- User is logged in
- User is on main page  

**Type:** Functional

**Steps:**
1.  Click on the menu button
2.  click on the "about" section in the menu

**Expected Result:** User went to the about page

### TC-10: Logout
**Preconditions:** 
- User is logged in
- User is on main page  

**Type:** Functional

**Steps:**
1.  Click on the menu button
2.  click on the "Logout" section in the menu

**Expected Result:** User is on login page


### TC-N-01: Checkout with invalid name
**Preconditions:** 
- User is logged in
- User is on Checkout page

**Type:** Negative  

**Steps:**
1. Enter numbers in name field
2. Enter your Last name
3. Enter your postal code
4. Click continue

**Expected Result:** User sees the error message

### TC-N-02: Checkout with invalid last name
**Preconditions:** 
- User is logged in
- User is on Checkout page

**Type:** Negative  

**Steps:**
1. Enter your name 
2. Enter numbers in Last name field
3. Enter your postal code
4. Click continue

**Expected Result:** User sees the error message

### TC-N-03: Checkout with invalid postal code
**Preconditions:** 
- User is logged in
- User is on Checkout page

**Type:** Negative  

**Steps:**
1. Enter your name 
2. Enter your Last name
3. Enter letters in postal code field
4. Click continue

**Expected Result:** User sees the error message


### TC-N-04: Checkout with Arabic name
**Preconditions:** 
- User is logged in
- User is on Checkout page

**Type:** Negative  

**Steps:**
1. Enter Arabic characters in the First Name field
2. Enter valid Last Name
3. Enter valid Postal Code
4. Click Continue

**Expected Result:** User sees the error message
