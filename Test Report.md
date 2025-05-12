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


<img width="844" alt="Screenshot 2025-05-11 at 16 46 29" src="https://github.com/user-attachments/assets/87be7d4f-6fa7-4ce5-bd7a-2eda30531c86" />

### scenario 2: Verify shipping cost changes.
**Test Case:** Verify that free shipping is applied if the total product cost is greater than or equal to 20 euros
  | step# | Action                                          | Expected outcome                                                  | Ok/NOK | URL                                                                   | Link Issue to |   |   |   |
|-------|-------------------------------------------------|-------------------------------------------------------------------|--------|-----------------------------------------------------------------------|---------------|---|---|---|
| 1     | Go to login page Grocery mate                   | login page appears                                                | OK     | https://grocerymate.masterschool.com                                  |               |   |   |   |
| 2     | Clik on login icon                              | you are directed to login page                                    | OK     |                                                                       |               |   |   |   |
| 3     | Fill in user name and password                  |                                                                   | OK     |                                                                       |               |   |   |   |
| 4     | Click on sign in button                         | user is redirected to the homepage with loged in status           | OK     |                                                                       |               |   |   |   |
| 5     | Click on the shop menu item                     | shope page is displayed                                           | OK     |                                                                       |               |   |   |   |
| 6     | Add a product to the cart                       | the product is added to the cart                                  | OK     |                                                                       |               |   |   |   |
| 7     | Click on the cart                               | The shipping cost fee changes of product is displayed             | OK     |                                                                       |               |   |   |   |
| 8     |  buy a product cost > 20$ to get free shipment  | the product cost is 21$ and free shipment is successfully applied | OK     |           


### Scenario 3: Age verification for Alcoholic products.
Test Case 1:** Verify that a user below the legal drinking age cannot purchase alcoholic products.

| 1 | Action                                         | Expected outcome                                                                 | OK/NOK | URL                                       | Link to Issue |
|---|------------------------------------------------|----------------------------------------------------------------------------------|--------|-------------------------------------------|---------------|
| 2 | Go to login page GroceryMate                   | Login page appears                                                               | OK     | https://grocerymate.masterschool.com/     |               |
| 3 | Click on login Icon                            | You are directed to login page                                                   | OK     | https://grocerymate.masterschool.com/auth |               |
| 4 | Fill in username                               |                                                                                  | OK     |                                           |               |
| 5 | Fill in password                               |                                                                                  | OK     |                                           |               |
| 6 | click on sign in button                        | user is redirefted to the homepage with logged in status                         | OK     |                                           |               |
| 7 |Enter DOB that makes user 20 years old                       | Age is applied and system accepts to purchase Alcoholic products                                                          | OK     |                                           |               |
| 8 |Click on the Alcoholic menu items           | Alcoholic products is successfully purchased         | OK     |                                          
