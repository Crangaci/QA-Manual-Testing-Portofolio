# Test Cases - Online Gadget Store

## TC_001 - Create a new account

Test Scenario: TS_001

Preconditions:
User is on the registration page.

Steps:
1. Open registration page
2. Enter valid name
3. Enter valid email address
4. Enter valid password
5. Click "Register" button

Expected Result:
User account is created successfully.

Status:
Not Tested


## TC_002 - Login with valid credentials

Test Scenario: TS_002

Preconditions:
User has an existing account.

Steps:
1. Open login page
2. Enter valid email and password
3. Click "Login" button

Expected Result:
User is successfully logged into the account.

Status:
Not Tested


## TC_003 - Login with invalid credentials

Test Scenario: TS_003

Preconditions:
User is on the login page.

Steps:
1. Enter incorrect email or password
2. Click "Login" button

Expected Result:
Error message is displayed.

Status:
Not Tested


## TC_004 - User logout

Test Scenario: TS_004

Preconditions:
User is logged into the account.

Steps:
1. Click "Logout" button

Expected Result:
User is logged out successfully.

Status:
Not Tested


## TC_005 - Search for a product

Test Scenario: TS_006

Preconditions:
User is on the homepage.

Steps:
1. Enter product name in search field
2. Click search button

Expected Result:
Relevant products are displayed.

Status:
Not Tested


## TC_006 - Open product details

Test Scenario: TS_008

Preconditions:
Products are displayed on the website.

Steps:
1. Select a product
2. Open product page

Expected Result:
Product details are displayed correctly.

Status:
Not Tested


## TC_007 - Add product to shopping cart

Test Scenario: TS_011

Preconditions:
User is on the product page.

Steps:
1. Select a product
2. Click "Add to Cart" button

Expected Result:
Product is added to the shopping cart.

Status:
Not Tested


## TC_008 - Remove product from shopping cart

Test Scenario: TS_013

Preconditions:
Product exists in the shopping cart.

Steps:
1. Open shopping cart
2. Click "Remove" button

Expected Result:
Product is removed from the cart.

Status:
Not Tested


## TC_009 - Update product quantity

Test Scenario: TS_014

Preconditions:
Product exists in the shopping cart.

Steps:
1. Open shopping cart
2. Change product quantity

Expected Result:
Product quantity and total price are updated.

Status:
Not Tested


## TC_010 - Checkout process

Test Scenario: TS_016

Preconditions:
User has products in the shopping cart.

Steps:
1. Open shopping cart
2. Click "Checkout"
3. Enter required information
4. Confirm order

Expected Result:
Order is completed successfully.

Status:
Not Tested


## TC_011 - View product reviews

Test Scenario: TS_020

Preconditions:
Product page is opened.

Steps:
1. Scroll to reviews section

Expected Result:
Product reviews are displayed.

Status:
Not Tested


## TC_012 - Submit product review

Test Scenario: TS_021

Preconditions:
User is logged into the account.

Steps:
1. Open product reviews section
2. Enter review text
3. Click "Submit"

Expected Result:
Review is added successfully.

Status:
Not Tested


## TC_013 - Check website navigation

Test Scenario: TS_010

Preconditions:
User is on the homepage.

Steps:
1. Click menu links
2. Open different website pages

Expected Result:
All navigation links work correctly.

Status:
Not Tested


## TC_014 - Check website images

Test Scenario: TS_025

Preconditions:
User opens website pages.

Steps:
1. Open pages with images

Expected Result:
All images are displayed correctly.

Status:
Not Tested

# Additional Test Cases - Online Gadget Store

## TC_015 - Verify search with invalid product name

Test Scenario: TS_007

Preconditions:
User is on the website homepage.

Steps:
1. Enter an unavailable product name in the search field
2. Click the search button

Expected Result:
A message is displayed that no products were found.

Status:
Not Tested


## TC_016 - Verify product information

Test Scenario: TS_009

Preconditions:
User is on a product details page.

Steps:
1. Open a product page
2. Check product name
3. Check product price
4. Check product description
5. Check product image

Expected Result:
All product information is displayed correctly.

Status:
Not Tested



## TC_017 - Verify empty shopping cart

Test Scenario: TS_012

Preconditions:
User has no products in the cart.

Steps:
1. Open shopping cart page

Expected Result:
Empty cart message is displayed.

Status:
Not Tested


## TC_018 - Verify quantity limit in shopping cart

Test Scenario: TS_014

Preconditions:
Product is added to the shopping cart.

Steps:
1. Increase product quantity
2. Check quantity value

Expected Result:
Quantity is updated correctly according to the allowed limit.

Status:
Not Tested


## TC_019 - Verify checkout with empty required fields

Test Scenario: TS_017

Preconditions:
User is on the checkout page.

Steps:
1. Leave required fields empty
2. Click "Place Order" button

Expected Result:
Validation messages are displayed.

Status:
Not Tested


## TC_020 - Verify order confirmation message

Test Scenario: TS_019

Preconditions:
User completed checkout successfully.

Steps:
1. Complete the order
2. Check confirmation page

Expected Result:
Order confirmation message is displayed.

Status:
Not Tested


## TC_021 - Verify review with empty text

Test Scenario: TS_021

Preconditions:
User is on the product review section.

Steps:
1. Leave review field empty
2. Click "Submit Review"

Expected Result:
Validation message is displayed.

Status:
Not Tested


## TC_022 - Verify buttons functionality

Test Scenario: TS_024

Preconditions:
User is on the website.

Steps:
1. Click main buttons on the website
2. Check button actions

Expected Result:
All buttons perform the correct actions.

Status:
Not Tested


## TC_023 - Verify website layout on mobile device

Test Scenario: TS_028

Preconditions:
User opens the website on a mobile device.

Steps:
1. Open website using mobile browser
2. Check page layout
3. Check menus and buttons

Expected Result:
Website is displayed correctly on mobile devices.

Status:
Not Tested



## TC_024 - Verify browser compatibility

Test Scenario: TS_026

Preconditions:
Website is available.

Steps:
1. Open website in Google Chrome
2. Open website in Mozilla Firefox
3. Compare functionality

Expected Result:
Website works correctly in different browsers.

Status:
Not Tested
