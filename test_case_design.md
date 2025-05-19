# Test Case design: GroceryMate
The software under test is https://grocerymate.masterschool.com

## Product Rating System
Test Design Techniques: Boundary Value Analysis, Equivalence Partitioning, Error Guessing 

### Boundary Value Analysis(BVA),

**Test Case:** Verify submitting a 5-star rating 

- Input: select 5 stars
- Expected outcome: Rating is selected and displayed correctly

Equivalence Equivalence partitioning(EP),error Guessing

**Test Cases: Verify submitting a 1-star rating

- Input: select 1 star
- Expected outcome: Rating is selected and displayed correctly

### Feature 2: Shipping Cost Changes

- Test Design Techniques: Boundary Value Analysis, Equivalence Partitioning, Error Guessing

#### Boundary Value Analysis

** Test Case:** Verify that free shipping is applied if the total product cost is greater than or equal to 20 euros
- Input: add products to the cart so that the total cost is above 20 euros
- Expected outcome: No shipping cost is applied

** Test Case:** Verify that the shipping fee is applied if the total cost is less than 20 euros 
-- Input: add products to the cart so that the total cost is 19 euros
- Expected outcome: The correct shipping fee is applied

#### Age verification:

** Test Case 1:** Verify that a user below the legal drinking age cannot purchase alcoholic products.

- Input: Enter a date of birth that results in an age below the legal drinking age, or enter a DOB that makes the age under 18.
-  Expected Outcome: The system should prevent the purchase and display a message stating that the user is not old enough.

** Test Case 2:**
 Verify that a user is of the legal drinking age and can purchase alcoholic products.
- Input: Enter a date of birth that results in the exact legal drinking age (e.g., 21). 
- Expected Outcome: The system should allow the purchase.


