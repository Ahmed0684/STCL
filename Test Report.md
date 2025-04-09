This document contains test execution of the test cases related to https:grocerymate.masterschool.com
### scenario 1: Verify submitting 1star rating.
As a user of GroceryMate, I am able to buy a product and give a 1 star rating. 
| Step# | Action                       | Expected outcome                                                   | OK/NOK | URL                                       | Link to Issue |
|-------|------------------------------|--------------------------------------------------------------------|--------|-------------------------------------------|---------------|
| 1     | Go to login page GroceryMate | Login page appears                                                 | OK     | https://grocerymate.masterschool.com/     |               |
| 2     | Click on login Icon          | You are directed to login page                                     | OK     | https://grocerymate.masterschool.com/auth |               |
| 3a    | Fill in username             |                                                                    | OK     |                                           |               |
| 3b    | Fill in password             |                                                                    | OK     |                                           |               |
| 3c    | click on sign in button      | user is redirefted to the homepage with logged in status           | OK     |                                           |               |
| 4     | Click on the menu item       | shop page is displayed. |                                          | OK     |                                           |               |
| 5     | Add a product to the cart    | product is added to to the cart and You are successfully logged in | OK     |                                           |               |





### scenario 2: Verify shipping cost changes.
As a user of GroceryMate, I am able to buy a product and make shipment. 
| 1  | Action                                              | Expected outcome                                         | OK/NOK | URL                                       | Link to Issue |
|----|-----------------------------------------------------|----------------------------------------------------------|--------|-------------------------------------------|---------------|
| 2  | Go to login page GroceryMate                        | Login page appears                                       | OK     | https://grocerymate.masterschool.com/     |               |
| 3  | Click on login Icon                                 | You are directed to login page                           | OK     | https://grocerymate.masterschool.com/auth |               |
| 4  | Fill in username                                    |                                                          | OK     |                                           |               |
| 5  | Fill in password                                    |                                                          | OK     |                                           |               |
| 6  | click on sign in button                             | user is redirefted to the homepage with logged in status | OK     |                                           |               |
| 7  | Click on the menu item                              | shop page is displayed.                                  | OK     |                                           |               |
| 8  | Add products to cart worth > 20€                    | No shipping cost is applied                              | OK     |                                           |               |
| 9  | Add products worth < 20€                            | Shipping fee is applied                                  | OK     |                                           |               |
| 10 | Add items worth 25€, remove one to drop total < 20€ | Shipping fee is applied correctly                        | OK     |                                           |               |
| 11 | Add item worth €9, increase quantity to exceed €20  | Shipping becomes free                                    | OK     |                                           |               |
| 12 | fill shipment adress and payment                    | Shipment adress and payment is fulfilled                 | OK     |                                           |               |
| 13 | Select buy now                                      | Buy now is selected                                      | Ok     |                                           |               |



### scenario 3: Age verification for Alcoholic products.
Test Case 1:** Verify that a user below the legal drinking age cannot purchase alcoholic products.

| 1 | Action                                         | Expected outcome                                                                 | OK/NOK | URL                                       | Link to Issue |
|---|------------------------------------------------|----------------------------------------------------------------------------------|--------|-------------------------------------------|---------------|
| 2 | Go to login page GroceryMate                   | Login page appears                                                               | OK     | https://grocerymate.masterschool.com/     |               |
| 3 | Click on login Icon                            | You are directed to login page                                                   | OK     | https://grocerymate.masterschool.com/auth |               |
| 4 | Fill in username                               |                                                                                  | OK     |                                           |               |
| 5 | Fill in password                               |                                                                                  | OK     |                                           |               |
| 6 | click on sign in button                        | user is redirefted to the homepage with logged in status                         | OK     |                                           |               |
| 7 | Click on the menu item                         | shop page is displayed.                                                          | OK     |                                           |               |
| 8 | Enter DOB that makes user 20 years old         |      System blocks purchase and shows “You are not old enough” message           | OK     |                                           |               |
| 9 | Enter DOB that makes user exactly 21 years old | System allows purchase                                                           | OK     |                                           |               |



