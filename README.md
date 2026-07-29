# Mercado Enlinia — E-Commerce Web Application

Mercado Enlinia is a full-stack e-commerce web application built using Java Enterprise technologies. It features a complete customer shopping workflow—from product discovery to checkout—alongside a dynamic admin dashboard for store management and automated email notifications.

# Project Overview

### User Features

-Authentication: Account registration and secure login.
-Product Catalog: Browse products with multi-category filtering and real-time search.
-Shopping Cart: Add items, adjust quantities on the fly, and update cart subtotals.
-Checkout & Payment: Interactive checkout process (includes a mock credit card integration for testing).
-Order Tracking: Detailed order summary and live shipping status updates.

### Admin Dashboard

-Product Management: Add, update, or remove inventory items.
-Inventory Control: Monitor stock levels in real time.
-Order Fulfillment: View all customer orders and update status from processing to Shipped or Delivered.

### Automated Email System

Welcome Email: Triggered upon successful registration.
Order Confirmation: Sent immediately after placing an order.
Shipping Updates: Dispatched when an order is marked as shipped or delivered.

### Note:
The payment gateway is designed strictly for demonstration purposes. Any test credit card credentials will successfully place an order.

### Technologies used:-
1. Front-End Development:
- HTML
- CSS
- Javascript
- BootStrap

2. Back-End Development:
- Java [JDK 8+]
- JDBC
- Servlet
- JSP

3. Database:
- MySql

### ================ Software And Tools Required ================
- : Git 
- : Java JDK 8+ 
- : Eclipse EE 
- : Apache Maven 
- : Tomcat v8.0+
- : MySQL Server 
- : MySQL Workbench 

### ================= Dummy Database Initialization =================
STEP 1: Open MySQL Command Prompt or MySQL Workbench

STEP 2: Login to the administrator user of MySql:
	 ```mysql -u <username> -p``` (Enter Password if asked)

STEP 3: Copy paste and execute the MySQL Query from the following file:-
- Run the Sql Query From this file: [databases/mysql_query.sql](./databases/mysql_query.sql)

### ======GENERATING GMAIL APP PASSWORD [For Mailing Functionalities]========
Step 1: Create a gmail account or login to existing account in any browser

Step 2 : Go to [https://myaccount.google.com/security](https://myaccount.google.com/security) and check if 2 step verifications is enabled or not, enable it if not enabled

Step 3: Go to [https://myaccount.google.com/apppasswords](https://myaccount.google.com/apppasswords) and enter password if asked

Step 4: In Select an App Section: select Other (custom name) => enter "Ellison Electronics" => Generate

Step 5: After that it will generate 16 digits app password which you need to copy and save for future configurations.

Step 6: Done : Now continue to importing the project. [Don't share the above password generated to anyone]

### ========== Importing and Running The Project Through Eclipse EE ==========

Step 1: Open Eclipse Enterprise Edition. [Install, if not already installed.]

Step 2: Click On File > Import > Git > Projects From Git > Clone Uri > Paste The Repository Url as: ```https://github.com/shashirajraja/shopping-cart.git```> Select master Branch > Next > Next > Finish.

Step 3: Go inside ```Java Resources > src > application.properties``` and update the values as below:
- a) Update value for db.username and db.password according to your installed mysql credentials.
- b) Update value for mailer.email and mailer.password, with the same email and app password that you generated earlier in above section [ NOTE:Actual gmail password will not work]

Step 4: Right Click on Project > Run as > Maven Build > In the goals field enter "clean install" > apply > run

Step 5: Right Click On Project > Build Path > Configure Build Path > Libraries > Remove and Update Any Libraries if Red Mark Exists > Finish.

Step 6: Right Click on Project > maven > update project > select force update > apply > close

Step 7: Tomcat Configurations:
- If Tomcat Server is not configured in Eclipse :
	-  Right Click On Project > Run As > Run On Server > Manually Define a new server > Select server type > select Tomcat v8.0+ > (Select Tomcat V8.0+ Installation Location If Asked) > Next > Add the current project > Finish.

- Else If Tomcat Server is already configured in Eclipse:
	- Right Click On Project > Run As > Run On Server > Select Tomcat Version > Next > Add the project > Finish.
		<p align='center'>or</p>
	- You can directly goto server tab, select the tomcat server and use the debug or run button to start the previously ran project

Step 8: Check Running The Site At  [http://localhost:8080/shopping-cart/](http://localhost:8080/shopping-cart/)

Step 9:  [To Change the Port, if getting error like 'port already in use'] Open The Server Tab > Double Click On Tomcat Server > Ports > Change The Port Number For Http/1.1 To 8083 > Close And Save. Now Start and you can access the project on [http://localhost:8083/shopping-cart/](http://localhost:8083/shopping-cart/)

Step 10: Default Username And Password For Admin Is "admin@gmail.com" And "admin"

Step 11: The default Username And Password For User Is "guest@gmail.com" And "guest"

"# Mercado-Enlinia" 
"# Mercado-Enlinia" 
"# Mercado-Enlinia" 
"# Mercado-Enlinia" 
"# Mercado-Enlinia" 

