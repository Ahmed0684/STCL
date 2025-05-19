**Test Case:** Verify submitting a 1-star rating 

- Input: select 1-star
- Expected outcome: Rating is selected and displayed correctly


| step# | Action                                                                  | Expected outcome                                         | Ok/NOK | URL                                                                   | Link Issue to |   |   |   |
|-------|-------------------------------------------------------------------------|----------------------------------------------------------|--------|-----------------------------------------------------------------------|---------------|---|---|---|
| 1     | Go to login page Grocery mate                                           | login page appears                                       | OK     | https://grocerymate.masterschool.com                                  |               |   |   |   |
| 2     | Clik on login icon                                                      | you are directed to login page                           | OK     |                                                                       |               |   |   |   |
| 3     | Fill in user name and password                                          |                                                          | OK     |                                                                       |               |   |   |   |
| 4     | Click on sign in button                                                 | user is redirected to the homepage with loged in status  | OK     |                                                                       |               |   |   |   |
| 5     | Click on the shop menu item                                             | shope page is displayed                                  | OK     |                                                                       |               |   |   |   |
| 6     | Add a product to the cart                                               | the product is added to the cart                         | OK     |                                                                       |               |   |   |   |
| 7     | Click on the cart to enter the shipment address and payment.          | The product is successfully bought.                      | OK     |                                                                       |               |   |   |   |
| 8     | Click on your bought product and select a 1-star rating. | One star rating is successfully selected. | OK     | https://grocerymate.masterschool.com/product/66b3a57b3fd5048eacb47998 |               |   |   |   

**Test Case:** Verify submitting a 5-star rating 

- Input: select 5-star
- Expected outcome: Rating is selected and displayed correctly


| step# | Action                                                                  | Expected outcome                                         | Ok/NOK | URL                                                                   | Link Issue to |   |   |   |
|-------|-------------------------------------------------------------------------|----------------------------------------------------------|--------|-----------------------------------------------------------------------|---------------|---|---|---|
| 1     | Go to login page Grocery mate                                           | login page appears                                       | OK     | https://grocerymate.masterschool.com                                  |               |   |   |   |
| 2     | Clik on login icon                                                      | you are directed to login page                           | OK     |                                                                       |               |   |   |   |
| 3     | Fill in user name and password                                          |                                                          | OK     |                                                                       |               |   |   |   |
| 4     | Click on sign in button                                                 | user is redirected to the homepage with loged in status  | OK     |                                                                       |               |   |   |   |
| 5     | Click on the shop menu item                                             | shope page is displayed                                  | OK     |                                                                       |               |   |   |   |
| 6     | Add a product to the cart                                               | the product is added to the cart                         | OK     |                                                                       |               |   |   |   |
| 7     | Click on the cart to enter the shipment address and payment.          | The product is successfully bought.                      | OK     |                                                                       |               |   |   |   |
| 8     | Click on your bought product and select a 5-star rating. | One star rating is successfully selected. | O
                                                                                                                    




<img width="844" alt="Screenshot 2025-05-11 at 16 46 29" src="https://github.com/user-attachments/assets/87be7d4f-6fa7-4ce5-bd7a-2eda30531c86" /  

### scenario 2: Verify shipping cost changes.
**Test Case:** Verify that free shipping is applied if the total product cost is greater than 20 euros
| 1  | Action                                              | Expected outcome                                         | OK/NOK | URL                                       | Link to Issue |
|----|-----------------------------------------------------|----------------------------------------------------------|--------|-------------------------------------------|---------------|
| 2  | Go to login page GroceryMate                        | Login page appears                                       | OK     | https://grocerymate.masterschool.com/     |               |
| 3  | Click on login Icon                                 | You are directed to login page                           | OK     | https://grocerymate.masterschool.com/auth |               
| 4  | Fill in username                                    |                                                          | OK     |                                           |               |
| 5  | Fill in password                                    |                                                          | OK     |                                           |               |
| 6  | click on sign in button                             | user is redirefted to the homepage with logged in status | OK     |                                           |               |
| 7  | Click on the menu item                              | shop page is displayed.                                  | OK     |                                           |               |
| 8  | Add products to cart worth 21€                    | No shipping cost is applied                              | OK                                       |               |
| 9 | fill shipment adress and payment                    | Shipment adress and payment is fulfilled  | OK                                    |
| 12 | Select buy now button                                      | Buy now is selected and shipped to the user's address|    OK      |               |                |


### scenario 2: Verify shipping cost changes.
**Test Case:** Verify that free shipping is applied if the total product cost is greater than or equal to 20 euros
| 1  | Action                                              | Expected outcome                                         | OK/NOK | URL                                       | Link to Issue |
|----|-----------------------------------------------------|----------------------------------------------------------|--------|-------------------------------------------|---------------|
| 2  | Go to login page GroceryMate                        | Login page appears                                       | OK     | https://grocerymate.masterschool.com/     |               |
| 3  | Click on login Icon                                 | You are directed to login page                           | OK     | https://grocerymate.masterschool.com/auth |               |
| 4  | Fill in username                                    |                                                          | OK     |                                           |               |
| 5  | Fill in password                                    |                                                          | OK     |                                           |               |
| 6  | click on sign in button                             | user is redirefted to the homepage with logged in status | OK     |                                           |               |
| 7  | Click on the menu item                              | shop page is displayed.                                  | OK     |                                           |               |
| 8  | Add products to cart worth 19€                    | shipping fee is applied                              | OK                                       |               |
| 9 | fill shipment adress and payment                    | Shipment adress and payment is fulfilled  | OK                                    |
| 12 | Select buy now button                                      | Buy now is selected and successfully shipped to the user's address|    OK      |               |                |

<img width="618" alt="Screenshot 2025-05-12 at 23 55 30" src="https://github.com/user-attachments/assets/69d4ec12-a242-41f1-bcee-3bc2b61718eb" />


### Scenario 3: Age verification for Alcoholic products.
** Test Case:**
 Verify that a user is of the legal drinking age and can purchase alcoholic products.
- Input: Enter a date of birth for which the user is of legal of alcoholic drinking age ( 21 years). 
- Expected Outcome: The system should allow the purchase.
| 1 | Action                                         | Expected outcome                                                                 | OK/NOK | URL                                       | Link to Issue |
|---|------------------------------------------------|----------------------------------------------------------------------------------|--------|-------------------------------------------|---------------|
| 2 | Go to login page GroceryMate                   | Login page appears                                                               | OK     | https://grocerymate.masterschool.com/     |               |
| 3 | Click on login Icon                            | You are directed to login page                                                   | OK     | https://grocerymate.masterschool.com/auth |               |
| 4 | Fill in username                               |                                                                                  | OK     |                                           |               |
| 5 | Fill in password                               |                                                                                  | OK     |                                           |               |
| 6 | click on sign in button                        | user is redirefted to the homepage with logged in status                         | OK     |                                           |               |
| 7 |Enter DOB that user is 21 years old                       | Age is applied and system accepts to purchase Alcoholic products                                                          | OK     |                                           |               |
| 8 |Click on the Alcoholic menu items           | Alcoholic products is successfully purchased         | OK     |                                          

### Scenario 3: Age verification for Alcoholic products.
** Test Case:**
 Verify that a user is of the legal drinking age and can not purchase alcoholic products.
- Input: Enter a date of birth for which the user is of legal of alcoholic drinking age ( 17 years). 
- Expected Outcome: The system should deny the purchase.


| 1 | Action                                         | Expected outcome                                                                 | OK/NOK | URL                                       | Link to Issue |
|---|------------------------------------------------|----------------------------------------------------------------------------------|--------|-------------------------------------------|---------------|
| 2 | Go to login page GroceryMate                   | Login page appears                                                               | OK     | https://grocerymate.masterschool.com/     |               |
| 3 | Click on login Icon                            | You are directed to login page                                                   | OK     | https://grocerymate.masterschool.com/auth |               |
| 4 | Fill in username                               |                                                                                  | OK     |                                           |               |
| 5 | Fill in password                               |                                                                                  | OK     |                                           |               |
| 6 | click on sign in button                        | user is redirefted to the homepage with logged in status                         | OK     |                                           |               |
| 7 |Enter DOB that user is 17 years old                       | Age is applied and system denied to purchase Alcoholic products                                                          | OK     |                                           |               |
| 8 |Click on the Alcoholic menu items           | Alcoholic products is successfully purchased         | OK     |                                          
