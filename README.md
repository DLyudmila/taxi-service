# :oncoming_taxi: **taxi-service** :oncoming_taxi: 
<br/>**Project description:**
<br/>The taxi-service application will help you to store data about drivers, cars and manufacturers in the database and display the information in a comfortable way. This application allows you to register a new user(driver), it provides user's authentication and access to different CRUD operations. You may create relations between manufacturers and cars, cars and drivers.
<br/>
<br/>**Features:**
<br/>:arrow_forward: registration like a driver
<br/>:arrow_forward: authentication like a driver
<br/>:arrow_forward: create/update/remove a manufacturer
<br/>:arrow_forward: create/update/remove a driver
<br/>:arrow_forward: create/update/remove a car
<br/>:arrow_forward: create/update/remove add driver to a car
<br/>:arrow_forward: display list of cars by a driver
<br/>:arrow_forward: display all cars/drivers/manufacturers
<br/>
<br/>**Technologies that were used in the project:**
<br/>- JDBC, 
<br/>- Servlet, 
<br/>- JSTL, 
<br/>- JSP, 
<br/>- HTML, 
<br/>- CSS,
<br/>- MySql Workbench 8.0 CE,
<br/>- TomCat 9.0.63,
<br/>- Logger log4j
<br/>
<br/>:eyes: **How to launch the project:**
- To get the actual parameters of the database tables, run script from the resources/init_db.sql file in the Workbench
- Establish connection to your Database. Open ConnectionUtil class and write appropriate URL, USERNAME, PASSWORD and JDBC_DRIVER.  
- Let's install Tomcat 9.0.63
- Run the project using configuration TomCat local server. Choose artifact: taxi-service: war exploded.
