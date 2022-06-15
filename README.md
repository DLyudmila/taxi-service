:oncoming_taxi: # **taxi-service** :oncoming_taxi: 
**Project description:**
A simple web-application that supports authentication, registration and other CRUD operations
**Features:**
:arrow_forward: registration like a driver
:arrow_forward: authentication like a driver
:arrow_forward: create/update/remove a manufacturer
:arrow_forward: create/update/remove a driver
:arrow_forward: create/update/remove a car
:arrow_forward: create/update/remove add driver to a car
:arrow_forward: display list of cars by a driver
:arrow_forward: display all cars/drivers/manufacturers
**Technologies that were used in the project:**
- Intellij IDEA Ultimate 2022.1.2
- MySql Workbench 8.0 CE
- TomCat 9.0.63
:eyes: **How to launch the project:**
- To get the actual parameters of the database tables, run script from the resources/init_db.sql file in the Workbench
- Check that you use Intellij IDEA Ultimate edition
- Let's install Tomcat 9.0.63
- Run the project using configuration TomCat local server. Choose artifact: taxi-service: war exploded. (Important! Change the url in application context to "/") 
