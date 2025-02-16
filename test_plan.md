# Test Plan for Grocery Website
## Objective:
The goal of this test plan is to ensure that the basic functionalities of the grocery website work correctly.<br>
This includes user registration, product search, adding items to the cart, and the checkout process.

### What will be tested:

- User Registration and Login
- Searching for Products
- Adding Products to the Cart
- Checking Out and Making Payments
- Adding Favorites
- User Profile Management
- Adding Promotions
   
## Analyze the Product:

### Objective:

The primary objective of the grocery website is to provide users with a seamless shopping experience, from searching for products to completing purchases.

### User Base:

The product will be used by a wide range of users, including individuals who prefer online grocery shopping.
It should cater to users on various devices such as PCs, laptops, smartphones, and tablets.

## Hardware and Software Specifications

### Hardware Requirements:

Devices: PCs, laptops, smartphones, tablets
Specifications: Standard configurations for Android and iOS devices,

## Software Requirements:

- Operating Systems: Windows, macOS, Android, iOS
- Browsers: Chrome, Firefox, Safari, Edge
- Dependencies: Payment gateways, backend services
- Product Functionality

## The product allows users to:

- Register and login
- Search and filter products
- Add products to the cart
- Complete the checkout process
- Manage favorites and user profiles
- Apply for promotions during checkout
   
## Test Strategy:

### Scope of Testing:

#### In scope

- User Registration and Login
- Product Search and Filtering
- Adding Products to the Cart
- Checkout Process
- Favorites Feature
- User Profile Management
- Promotions and Discounts

#### Out of Scope:

Backend operations not affecting the user interface
Integration with third-party payment gateways (unless directly related to checkout)

#### Type of Testing

- [x] Manual Testing
- [x] Basic Automation (Optional)
- [x] Functional Testing
- [x] Regression Testing
- [x] Usability Testing
- [x] Risks and Issues

Delays in feature development
Mitigation: Adjust the testing schedule accordingly.
Limited access to various devices
Mitigation: Focus on testing on the most common devices and browsers.

### Test Objectives:

#### Objectives:

Functionality: Ensure all core functionalities work as intended.

GUI: 
Verify that the graphical user interface is user-friendly and responsive.
Usability: Assess the ease of use for all website features.

#### Expected Outcomes

Functionality: All tested features perform correctly according to specifications.
GUI: The interface is intuitive and responsive.
Usability: Users can navigate and use the website easily.
5. Test Criteria
Suspension Criteria

Testing will be suspended if critical defects are found that block further testing.
Lack of necessary resources or test environment failures.

#### Exit Criteria

All planned tests have been executed.
At least 90% of executed test cases have passed.
All critical defects have been resolved.
No severity 1 or severity 2 defects remain open.

### Resource Planning
#### Human Resources:

- Test Manager
- QA Engineers
- Hardware:
- PCs, laptops, smartphones, tablets
- Software:
- Browsers: Chrome, Firefox, Safari, Edge
- Operating Systems: Windows, macOS, Android, iOS
- Infrastructure:
- Test environments with real devices and browsers

### Plan Test Environment
#### Test Environments:

- [x] Development (DEV)
- [x] Testing (TEST)
- [x] Acceptance (ACC)
- [x] Production (PROD)
- [x] Environment Setup:

Real devices with installed browsers and operating systems to simulate user conditions.
