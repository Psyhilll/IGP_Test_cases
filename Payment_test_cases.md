# Payment Processing Test Cases

## Test Case 1: Verify Successful Payment with a Valid Credit Card  
- **Test ID:** TC_PAYMENT_001  
- **Description:** Verify that a user can successfully complete a purchase using a valid credit card.  
- **Preconditions:**  
  - User must be logged in.  
  - At least one product should be in the cart.  
  - User must have a valid credit card.  
- **Test Steps:**  
  1. Open the IGP.com website and add a product to the cart.  
  2. Proceed to checkout.  
  3. Enter valid billing details.  
  4. Select "Credit Card" as the payment method.  
  5. Enter a valid credit card number, expiry date, and CVV.  
  6. Click "Pay Now".  
- **Expected Result:** The transaction should be successful, and the user should receive an order confirmation.  
- **Status:** Pending  

## Test Case 2: Verify Payment Failure with an Expired Credit Card  
- **Test ID:** TC_PAYMENT_002  
- **Description:** Verify that payment fails when an expired credit card is used.  
- **Preconditions:**  
  - User must be logged in.  
  - At least one product should be in the cart.  
  - User must have an expired credit card.  
- **Test Steps:**  
  1. Open the IGP.com website and add a product to the cart.  
  2. Proceed to checkout.  
  3. Enter valid billing details.  
  4. Select "Credit Card" as the payment method.  
  5. Enter an expired credit card number, expiry date, and CVV.  
  6. Click "Pay Now".  
- **Expected Result:** The system should display an error message: "Payment failed. Expired card."  
- **Status:** Pending  

## Test Case 3: Verify Payment Failure with Insufficient Balance  
- **Test ID:** TC_PAYMENT_003  
- **Description:** Verify that payment fails if the user has insufficient funds.  
- **Preconditions:**  
  - User must be logged in.  
  - At least one product should be in the cart.  
  - User must have a debit/credit card with insufficient funds.  
- **Test Steps:**  
  1. Open the IGP.com website and add a product to the cart.  
  2. Proceed to checkout.  
  3. Enter valid billing details.  
  4. Select "Debit Card" as the payment method.  
  5. Enter card details with an insufficient balance.  
  6. Click "Pay Now".  
- **Expected Result:** The system should display an error message: "Payment failed. Insufficient funds."  
- **Status:** Pending  

## Test Case 4: Verify Payment via Digital Wallet (PayPal, Google Pay)  
- **Test ID:** TC_PAYMENT_004  
- **Description:** Verify that a user can complete a purchase using a digital wallet.  
- **Preconditions:**  
  - User must be logged in.  
  - At least one product should be in the cart.  
  - User must have a valid digital wallet account.  
- **Test Steps:**  
  1. Open the IGP.com website and add a product to the cart.  
  2. Proceed to checkout.  
  3. Enter valid billing details.  
  4. Select "PayPal" or "Google Pay" as the payment method.  
  5. Authenticate and confirm the payment.  
- **Expected Result:** The transaction should be successful, and the user should receive an order confirmation.  
- **Status:** Pending  
