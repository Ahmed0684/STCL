# Test Case design: GroceryMate
The software under test is https://grocerymate.masterschool.com

## Product Rating System
Test Design Techniques: Boundary Value Analysis, Equivalence Partitioning, Error Guessing 

### Boundary Value Analysis(BVA),

**Test Case: ** Verify submitting a 5-star rating 

- Input: select 5 stars
- Expected outcome: Rating is selected and displayed correctly

Equivalence Equivalence partitioning(EP),error Guessing

**Test Cases:** Verify submitting a 1-star rating

- Input: select 1 star
- Expected outcome: Rating is selected and displayed correctly

### Feature 2: Shipping Cost Changes

- Test Design Techniques: Boundary Value Analysis, Equivalence Partitioning, Error Guessing

#### Boundary Value Analysis

** Test Case:** Verify that free shipping is applied if the total product cost is greater than or equal to 20 euros
- Input: add products to the cart so that the total cost exceeds 20 euros
- Expected outcome: No shipping cost is applied

** Test Case:** Verify that the shipping fee is applied if the total cost is less than 20 euros 
Expected outcome: correct shipping fee is applied

#### Error Guessing

** Test Case:** Verify that the shipping cost is applied when the items are removed from the cart and the total cost becomes less than 20 euros
- Input: add products then try decreasing the quantity of the products from the cart so that the total cost becomes less than 20 euros 
- Expected outcome: shipping cost is applied correctly based on the new total cost

** Test Case:** Verify that the shipping fee is when the quantity of items is increased from the cart and the total cost becomes greater than 20 euros
- input: add products then try increasing the quantity of the products from the cart so that the total cost becomes greater than 20 euro  
- Expected outcome: correct shipping becomes free

#### Adding Products to the Cart:
** Test Case 1:** 
Verify that a user can add a product to the cart.

- Input: Click "Add to Cart" on a product page. Expected Outcome: The product is added to the cart. 

** Test Case 2:** 
Verify that the cart updates when multiple quantities are added.

- Input: Add 3 units of the same product. 
- Expected Outcome: The cart shows 3 units of the product. 

#### Error Guessing :

** Test case:**
 Verify that an error is shown when trying to add 0 quantity.

- Input: Set quantity to 0 and try to add to cart. 
- Expected Outcome: Error message "Quantity must be at least 1."

#### Checkout Process Test Cases:

** Test Case 1:** Verify that the user can proceed to checkout with products in the cart.

- Input: Click "Checkout" with items in the cart.
-  Expected Outcome: The user is directed to the checkout page.

** Test Case 2:**
 verify that the user can complete a purchase with valid payment details.

- Input: Enter valid credit card information. 
- Expected Outcome: Payment is successful, and order confirmation is displayed.

** Test Case 3/ Error Guessing:** 
 Verify that an error message is shown if the payment method is invalid.

-Input: Enter an expired credit card. -
Expected Outcome: Error message "Payment failed."

#### Adding Favorites:

**Test Case 1:**
 Verify that a user can add a product to favorites.

- Input: Click "Add to Favorites" on a product page.  
- Expected Outcome: The product is added to the favorites list. 

**Test Case 2:** 
Verify that an error is shown if trying to add a product to favorites without logging in.

- Input: Try to add a product to favorites without being logged in. 
- Expected Outcome: Prompt to log in or error message.
