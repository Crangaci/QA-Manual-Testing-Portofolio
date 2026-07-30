# Order Placement Test Cases

## Test Case 1: Enter shipping information

Test ID: TC_CHECKOUT_001

### Scenario: User can enter shipping information during checkout.

Steps:
1. Add a product to the shopping cart.
2. Open the checkout page.
3. Enter shipping details (name, address, phone number, etc.).

Result:
Shipping information is entered and saved successfully.

Status: Pass

## Test Case 2: Select payment method

Test ID: TC_CHECKOUT_002

### Scenario: User can select a payment method.

Steps:
1. Proceed to checkout.
2. Select an available payment method (Card payment or Cash on delivery).

Result:
The selected payment method is applied successfully.

Status: Pass


## Test Case 3: Enter card payment details

Test ID: TC_CHECKOUT_003

### Scenario: User can enter valid card payment information.

Steps:
1. Select card payment method.
2. Enter valid card details.
3. Continue checkout.

Result:
Card payment information is accepted successfully.

Status: Pass


## Test Case 4: Confirm cash payment option

Test ID: TC_CHECKOUT_004

### Scenario: User can select cash payment method.

Steps:
1. Proceed to checkout.
2. Select "Cash on Delivery" payment method.
3. Confirm the order.

Result:
The order is placed successfully and the user receives a message confirming that payment will be made in cash upon delivery.

Status: Pass


## Test Case 5: Verify order details before placing order

Test ID: TC_CHECKOUT_005

### Scenario: User can review order details before completing the purchase.

Steps:
1. Add products to the cart.
2. Proceed to checkout.
3. Review products, quantities, prices, shipping information, and total amount.

Result:
All order details are displayed correctly before placing the order.

Status: Pass


## Test Case 6: Place an order

Test ID: TC_CHECKOUT_006

### Scenario: User can successfully place an order.

Steps:
1. Complete checkout information.
2. Click the "Place Order" button.

Result:
The order is created successfully.

Status: Pass


## Test Case 7: Display order confirmation message

Test ID: TC_CHECKOUT_007

### Scenario: User receives confirmation after placing an order.

Steps:
1. Complete an order.
2. Check the confirmation page/message.

Result:
A confirmation message is displayed with order details and payment information.

Status: Pass
