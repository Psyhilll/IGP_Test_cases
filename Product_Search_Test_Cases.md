# Product Search Test Cases

## Test Case 1: Verify Search with Valid Product Name  
- **Test ID:** TC_SEARCH_001  
- **Description:** Verify that searching for an existing product returns correct results.  
- **Preconditions:** The product must be available in the IGP catalog.  
- **Test Steps:**  
  1. Open the IGP.com website.  
  2. Enter a valid product name (e.g., "Roses Bouquet") in the search bar.  
  3. Click the "Search" button or press Enter.  
- **Expected Result:** The correct product(s) should be displayed in the search results.  
- **Status:** Pending  

## Test Case 2: Verify Search with Invalid Product Name  
- **Test ID:** TC_SEARCH_002  
- **Description:** Verify that searching for a non-existent product shows a "No results found" message.  
- **Preconditions:** The product name should not exist in the catalog.  
- **Test Steps:**  
  1. Open the IGP.com website.  
  2. Enter a random/non-existent product name (e.g., "XYZ123Gift") in the search bar.  
  3. Click the "Search" button or press Enter.  
- **Expected Result:** The system should display a message: "No results found".  
- **Status:** Pending  

## Test Case 3: Verify Search with Special Characters  
- **Test ID:** TC_SEARCH_003  
- **Description:** Verify system behavior when searching with special characters.  
- **Preconditions:** None.  
- **Test Steps:**  
  1. Open the IGP.com website.  
  2. Enter special characters (e.g., "@#$%^&*") in the search bar.  
  3. Click the "Search" button or press Enter.  
- **Expected Result:** The system should display a message: "No results found" or ignore special characters and show relevant results.  
- **Status:** Pending  

## Test Case 4: Verify Search Suggestions  
- **Test ID:** TC_SEARCH_004  
- **Description:** Verify that search suggestions appear when typing a product name.  
- **Preconditions:** The product must be available in the catalog.  
- **Test Steps:**  
  1. Open the IGP.com website.  
  2. Start typing a product name in the search bar (e.g., "Choco").  
- **Expected Result:** The system should display relevant product suggestions (e.g., "Chocolate Cake", "Chocolate Hamper").  
- **Status:** Pending  
