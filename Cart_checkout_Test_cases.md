# Cart & Checkout Test Cases

## Test Case 1: Verify Adding a Product to the Cart  
- **Test ID:** TC_CART_001  
- **Description:** Verify that a user can successfully add a product to the cart.  
- **Preconditions:** The product must be available in stock.  
- **Test Steps:**  
  1. Open the IGP.com website.  
  2. Search for a product.  
  3. Click on the product to open its details page.  
  4. Click "Add to Cart".  
- **Expected Result:** The product should be added to the cart, and a success message should be displayed.  
- **Status:** Pending  

## Test Case 2: Verify Removing a Product from the Cart  
- **Test ID:** TC_CART_002  
- **Description:** Verify that a user can remove an item from the cart.  
- **Preconditions:** There must be at least one product in the cart.  
- **Test Steps:**  
  1. Open the IGP.com website.  
  2. Add a product to the cart.  
  3. Go to the cart page.  
  4. Click on "Remove" or "Delete" for the selected product.  
- **Expected Result:** The product should be removed from the cart, and the cart count should update.  
- **Status:** Pending  

## Test Case 3: Verify Checkout Process with Valid Details  
- **Test ID:** TC_CHECKOUT_001  
- **Description:** Verify that a user can successfully complete a purchase with valid details.  
- **Preconditions:**  
  - User must be logged in.  
  - At least one product should be in the cart.  
- **Test Steps:**  
  1. Open the IGP.com website.  
  2. Add a product to the cart and proceed to checkout.  
  3. Enter valid shipping details (address, name, phone number).  
  4. Select a valid payment method.  
  5. Confirm the order.  
- **Expected Result:** The order should be successfully placed, and an order confirmation message should appear.  
- **Status:** Pending  

## Test Case 4: Verify Checkout with an Empty Cart  
- **Test ID:** TC_CHECKOUT_002  
- **Description:** Verify that checkout is not possible when the cart is empty.  
- **Preconditions:** The cart should be empty.  
- **Test Steps:**  
  1. Open the IGP.com website.  
  2. Go to the cart page.  
  3. Click on "Proceed to Checkout".  
- **Expected Result:** The system should display a message: "Your cart is empty. Please add items before checkout."  
- **Status:** Pending  
