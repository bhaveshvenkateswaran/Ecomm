# Automation-Testing-of-ECommerce-WebsiteUsingSelenium

- It’s demo project https://demo.nopcommerce.com/ , I used Selenium Framework in this project.

- Java
- Maven
- TestNG
- BDD
- DDT 
- POM (Page Object Model)
- Selenium Grid
- Sauce Labs
- Zalenium 
- Docker
- Allure Test Report
- Jenkins Pipeline
-  Slack Integration into Jenkins File

  
# Integrated Development Environment 
- Eclipse IDEA
- IntelliJ IDEA

  ## Automated Testing for an E-commerce Website

**Part 1: Test Planning**

**Test Strategy Document:**

**1. Objectives of testing:**

* Ensure core functionalities of the e-commerce website are working as intended.
* Identify any bugs or regressions before releasing new features or updates.
* Improve the user experience by testing for usability and accessibility.
* Build confidence in the website's performance under load.

**2. Scope of testing:**

* The entire e-commerce website, including all public pages and user functionalities.
* Integration with payment gateways and shipping services.
* Different browsers, operating systems, and devices (responsive design).

**3. Testing levels:**

* **Unit:** Testing individual components like login forms and product search functions.
* **Integration:** Testing how different components interact, like adding items to the cart and updating the checkout total.
* **System:** Testing the website as a whole, including user workflows like registration, purchase, and order tracking.
* **Acceptance:** Testing the website against user requirements and business goals.

**4. Testing types:**

* **Functional:** Testing core functionalities like product search, checkout, and user account management.
* **Usability:** Testing how easy and intuitive the website is for users to navigate and interact with.
* **Performance:** Testing the website's response time, loading speed, and scalability under different traffic loads.
* **Security:** Testing for vulnerabilities like SQL injection and unauthorized access.

**5. Entry and exit criteria:**

* **Entry:** Test cases are well-defined, documented, and reviewed.
* **Exit:** All test cases are executed, results documented, and critical bugs are fixed.

**6. Test environment and tools:**

* **Environment:** Local development environment with tools like Docker to replicate production settings.
* **Tools:** Selenium WebDriver for automated testing, Cypress for UI testing, JMeter for performance testing, and any relevant test data management tools.

**7. Risk analysis:**

* High priority: Payment processing errors, data loss, security vulnerabilities.
* Medium priority: Incorrect product information, broken links, usability issues.
* Low priority: Cosmetic bugs, minor visual inconsistencies.

**Test Plan:**

* **Deliverables:** Test strategy document, test cases, test execution reports, defect logs.
* **Schedule:** 4 weeks, divided into phases for planning, design, development, execution, and reporting.
* **Resources:** QA engineer, developer (for test environment setup and automation script support).
* **Test data and environment setup:**
    * Create test data files for different user roles and scenarios.
    * Set up a dedicated test environment with mock data for payment and shipping services.
* **Test execution and reporting:**
    * Execute tests manually and through automation scripts.
    * Log all test results, including screenshots and captured data.
    * Generate comprehensive reports with pass/fail rates, defect details, and recommendations.

**Part 2: Test Case Design**

**Functional Test Cases:**

* User registration and login
* Product search and filtering
* Adding items to cart and managing quantities
* Checkout process with different payment methods
* Order tracking and management
* Account settings and preferences
* Password reset and change
* Contact form and support channels

**Edge and Boundary Test Cases:**

* Empty search queries and invalid product IDs
* Adding large quantities of items to cart exceeding inventory levels
* Checkout with invalid payment information or exceeding credit limits
* Testing user account creation with special characters and maximum length passwords
* Testing responsiveness across different screen sizes and resolutions

**Part 3: Test Automation**

**Test Automation Framework:**

* **Selenium WebDriver:** Open-source, widely used, and supports multiple programming languages (Python, Java, Ruby).
* **Reason for selection:** Flexible, integrates with various testing tools, and offers extensive community support.

**Automated Test Scripts:**

* **Product search with multiple filters and sorting options.**
* **Adding items to cart from different product pages and categories.**
* **Checkout process with a pre-existing user account and credit card.**

**Test Data Management:**

* Use separate test data files for different user roles and scenarios.
* Implement data generation within scripts for dynamic test scenarios.
* Leverage mock APIs or database connections for payment and shipping simulations.



