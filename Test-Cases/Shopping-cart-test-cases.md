# Shopping Cart Test Cases

## Test Case 1: Add product to cart

Test ID: TC_CART_001

### Scenario: User can add a product to the shopping cart.

Steps:
1. Open product page
2. Select a product
3. Click Add to Cart button

Result:
The product is added successfully to the shopping cart.

Status: Pass


## Test Case 2: View added products in cart

Test ID: TC_CART_002

### Scenario: User can see added products in the shopping cart.

Steps:
1. Add a product to the cart
2. Open the shopping cart

Result:
The added product is displayed in the shopping cart.

Status: Pass


## Test Case 3: Display number of products in cart

Test ID: TC_CART_003

###Scenario: User can see the correct number of products added to the cart.

Steps:
1. Add one or more products to the cart
2. Open the shopping cart

Result:
The number of products in the cart is displayed correctly.

Status: Pass


## Test Case 4: Calculate total price in cart

Test ID: TC_CART_004

### Scenario: The system calculates the correct total price of products in the cart.

Steps:
1. Add a product to the cart
2. Open the shopping cart
3. Check the total price

Result:
The total price is calculated correctly based on the added products.

Status: Pass


## Test Case 5: Update product quantity in cart

Test ID: TC_CART_005

### Scenario: User can change the quantity of a product in the cart.

Steps:
1. Add a product to the cart
2. Open the shopping cart
3. Change product quantity

Result:
The quantity is updated and the total price is recalculated.

Status: Pass


## Test Case 6: Remove product from cart

Test ID: TC_CART_006

### Scenario: User can remove a product from the shopping cart.

Steps:
1. Open the shopping cart
2. Click Remove button for a product

Result:
The product is removed from the cart.

Status: Pass


## Test Case 7: Empty shopping cart

Test ID: TC_CART_007

### Scenario: User can see an empty cart message when there are no products.

Steps:
1. Open the shopping cart
2. Remove all products

Result:
A message is displayed that the shopping cart is empty.

Status: Pass
