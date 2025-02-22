# Order History & Tracking Test Cases

## Test Case 1: Verify Order Appears in Order History After Successful Purchase  
- **Test ID:** TC_ORDER_001  
- **Description:** Verify that a successfully placed order appears in the order history.  
- **Preconditions:**  
  - User must be logged in.  
  - User must have successfully placed an order.  
- **Test Steps:**  
  1. Open the IGP.com website.  
  2. Log in to the user account.  
  3. Navigate to the "My Orders" section.  
- **Expected Result:** The recently placed order should be visible in the order history with status "Processing" or "Shipped".  
- **Status:** Pending  

## Test Case 2: Verify Order Tracking Functionality  
- **Test ID:** TC_ORDER_002  
- **Description:** Verify that a user can track their order after purchase.  
- **Preconditions:**  
  - User must be logged in.  
  - User must have an order with a valid tracking number.  
- **Test Steps:**  
  1. Open the IGP.com website.  
  2. Log in to the user account.  
  3. Navigate to the "My Orders" section.  
  4. Click on a recent order and select "Track Order".  
- **Expected Result:** The tracking page should display real-time status updates like "Shipped", "Out for Delivery", or "Delivered".  
- **Status:** Pending  

## Test Case 3: Verify Order Cancellation Process  
- **Test ID:** TC_ORDER_003  
- **Description:** Verify that a user can cancel an order before it is shipped.  
- **Preconditions:**  
  - User must be logged in.  
  - The order status must be "Processing" (not yet shipped).  
- **Test Steps:**  
  1. Open the IGP.com website.  
  2. Log in to the user account.  
  3. Navigate to the "My Orders" section.  
  4. Select an order with "Processing" status.  
  5. Click "Cancel Order".  
  6. Confirm the cancellation.  
- **Expected Result:** The order should be canceled successfully, and the user should receive a confirmation email.  
- **Status:** Pending  

## Test Case 4: Verify Refund Process After Cancellation  
- **Test ID:** TC_ORDER_004  
- **Description:** Verify that a refund is processed after order cancellation.  
- **Preconditions:**  
  - User must have successfully canceled a prepaid order.  
- **Test Steps:**  
  1. Open the IGP.com website.  
  2. Log in to the user account.  
  3. Navigate to the "My Orders" section.  
  4. Check the status of the canceled order.  
- **Expected Result:** The system should display "Refund Initiated" or "Refund Processed", and the amount should be credited back within the expected timeframe.  
- **Status:** Pending  
