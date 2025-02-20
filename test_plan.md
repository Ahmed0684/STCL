## Test Plan for Grocery Website
### Objective:
The goal of this test plan is to ensure that the basic functionalities of the grocery website work correctly.
This includes user registration, product search, adding items to the cart, and the checkout process.

** What will be tested:**

- User Registration and Login
- Searching for Products
- Adding Products to the Cart
- Checking Out and Making Payments
- Adding Favorites
- User Profile Management
- Adding Promotions
- Analyze the Product:

** Objective:**

The primary objective of the grocery website is to provide users with a seamless shopping experience, from searching for products to completing purchases.

** User Base:**

The product will be used by a wide range of users, including individuals who prefer online grocery shopping. It should cater to users on various devices such as PCs, laptops, smartphones, and tablets.

#### Hardware and Software Specifications:

** Hardware Requirements:**

Devices: PCs, laptops, smartphones, tablets Specifications: Standard configurations for Android and iOS devices,

** Software Requirements:**

- Operating Systems: Windows, macOS, Android,iOS
- Browsers: Chrome, Firefox, Safari, Edge
- Dependencies: Payment gateways, backend services

** Product Functionality:**
The product allows users to:
- [x] Register and login
- [x] Search and filter products
- [x] Add products to the cart
- [x] Complete the checkout process
- [x] Manage favorites and user profiles
- [x] Apply for promotions during checkout

### Test Strategy:

** Scope of Testing:**
- In scope:
- User Registration and Login
- Product Search and Filtering
- Adding Products to the Cart
- Checkout Process
- Favorites Feature
- User Profile Management
- Promotions and Discounts

** Out of Scope:**

Backend operations not affecting the user interface Integration with third-party payment gateways (unless directly related to checkout)

#### Type of Testing:

** Manual Testing:**

-  Basic Automation (Optional)
-  Functional Testing
-  Regression Testing
-  Usability Testing

** Risks and Issues:**
Delays in feature development Mitigation: Adjust the testing schedule accordingly.
Limited access to various devices Mitigation: Focus on testing on the most common devices and browsers.

**Test Objectives:**

Objectives:

Functionality: Ensure all core functionalities work as intended.

- GUI: Verify that the graphical user interface is user-friendly and responsive. 
- Usability: Assess the ease of use for all website features.

- Expected Outcomes
Functionality: All tested features perform correctly according to specifications. 
- GUI: The interface is intuitive and responsive. 
- Usability: Users can navigate and use the website easily. 

** Test Suspension Criteria:** 

Testing will be suspended if critical defects are found that block further testing. 
Lack of necessary resources or test environment failures.

### Age Verification for Alcoholic Products:

#### Equivalence Partitioning (EP):

** Test case:** 

Verify that a user below the legal drinking age cannot purchase alcoholic products

- Input:  Enter a date of birth that results in an age below the legal drinking age (e.g., if the limit is 21, enter DOB that makes age 20).
- Expected Output: The system should prevent the purchase and display a message stating that the user is not old enough.

#### Boundary Value Analysis (BVA):

** Test case:** 
Verify that a user exactly at the legal drinking age can purchase alcoholic products

- Input: Enter a date of birth that results in the exact legal drinking age (e.g., 21).

- Expected Output: The system should allow the purchase

### Exit Criteria:

All planned tests have been executed. At least 90% of executed test cases have passed. All critical defects have been resolved. No severity 1 or severity 2 defects remain open.

- Resource Planning
- Human Resources:
- Test Manager
- QA Engineers
- Hardware:
- PCs, laptops, smartphones, tablets
- Software:
- Browsers: Chrome, Firefox, Safari, Edge
- Operating Systems: Windows, macOS, Android, iOS
- Infrastructure:
- Test environments with real devices and browsers
- Plan Test Environment
- Test Environments:
- Development (DEV)
- Testing (TEST)
- Acceptance (ACC)
- Production (PROD)

### Environment Setup:

Real devices with installed browsers and operating systems to simulate user conditions.
Risks and Issues
Delays in development
Mitigation: Implement a buffer period in the schedule.
Lack of test data
Mitigation: Create mock data sets for testing purposes.
Resource unavailability
Mitigation: Identify backup resources.
Test Logistics
Jane Smith - Test Manager
John Doe - QA Engineer (Functional and Regression Testing)
Alice Johnson - QA Engineer (Performance and Security Testing)
Robert Brown - QA Engineer (Usability Testing)
Maria Garcia - End User for UAT
3. Define Test Objectives
Objectives
Functionality: Ensure new features and existing functionalities work as intended.
GUI: Verify the graphical user interface for usability and consistency.
Performance: Confirm the system's performance under expected load conditions.
Security: Identify and mitigate potential security vulnerabilities.
Usability: Assess the user-friendliness of the platform.
Expected Outcomes
Functionality: All features perform correctly according to specifications.
GUI: The interface is intuitive, responsive, and free of defects.
Performance: The platform meets performance benchmarks under load.
Security: No significant vulnerabilities are detected.
Usability: Users can navigate and use the platform easily.
4. Define Test Criteria
Suspension Criteria
Testing will be suspended if critical defects are found that block further testing.
Lack of necessary resources or test environment failures.
Exit Criteria
All planned tests have been executed.
Run Rate: At least 95% of all test cases have been executed.
Pass Rate: At least 90% of executed test cases have passed.
All critical and high-priority defects have been resolved and closed.
No severity 1 or severity 2 defects are open.
Performance metrics meet the defined standards.
Security vulnerabilities have been identified and addressed.
User acceptance testing has been completed, and sign-off has been obtained.
5. Resource Planning
Human Resources: QA team, development team, end users for UAT
Hardware: PCs, laptops, smartphones, tablets
Software: Browsers (Chrome, Firefox, Safari, Edge), operating systems (Windows, macOS, Android, iOS)
Infrastructure: Test environments, automation tools, performance testing tools
6. Plan Test Environment
Test Environments: Real devices installed with real browsers and operating systems to simulate user conditions.
Environments: Development (DEV), Testing (TEST), Acceptance (ACC), Production (PROD)
7. Schedule and Estimation
Activity	Start Date	End Date	Environment	Responsible Person	Estimated Effort
Test Planning	01/08/2024	05/08/2024	All	Test Manager	20 hours
Test Case Design	06/08/2024	15/08/2024	All	QA Team	40 hours
Unit Testing	16/08/2024	25/08/2024	DEV	Development Team	60 hours
Integration Testing	26/08/2024	30/08/2024	TEST	QA Team	30 hours
System Testing	01/09/2024	10/09/2024	TEST	QA Team	80 hours
Regression Testing	11/09/2024	15/09/2024	TEST	QA Team	40 hours
Performance Testing	16/09/2024	18/09/2024	TEST	QA Team	20 hours
Security Testing	19/09/2024	21/09/2024	TEST	QA Team	20 hours
UAT	22/09/2024	30/09/2024	ACC	End Users	50 hours
Production Release	01/10/2024	01/10/2024	PROD	DevOps Team	10 hours
8. Determine Test Deliverables
Documents/tools that must be created to support testing activities in the project:

Test Plan Document
Test Cases and Test Scripts
Test Data
Test Reports
Defect Reports
UAT Sign-off Document
