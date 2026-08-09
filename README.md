**Introduction**
----------------
This project demonstrates my skills to automate the testing process for ecommerce website. The automation project is developed is using Python and Playwright written in POM format. 

Demo Web Shop is an online shopping platform designed to simulate a typical e-commerce store. Visitors can browse products, search for items, create an account, add products to a shopping cart or wishlist, and go through purchasing-related workflows. It is a demo e-commerce website called “Demo Web Shop”, operated as a Tricentis demo site and powered by nopCommerce.

For this demonstration, I have created few test cases to be automated. Some of the test cases are as below:

- TC0001 - Verify user able to end to end login/logout successfully with valid account.
- TC0002 - Verify user able to navigate to each item category at header.
- TC0003 - Verify user able to search for item in search bar.
- TCOOO4 - Verify user able to add items to the shopping cart successfully.
- TC0005 - Verify sum price of added items in the cart is correct.

**Getting started:**
----------------------
To run the project, you may:

1. Git clone this repository to your working directory.
2. Open this project using VSCode.
3. To run the code, use below command:
   For individual test case - pytest tests/cart/test_cart.py::test_total_price_in_cart_is_correct --headed --slowmo=100
5. A report file will be generated once test is finished running.
   To generate report -

**Environment:**
-----------------------
1. Playwright
2. Python
3. Pytest
4. Visual Code Studion
