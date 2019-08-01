Steps to install and run the application:

1. Pre-requisites

a. Install Java, JDK and set up path variables
b. Install Eclipse
c. Import this project as "Existing Maven Projects" (more detailed steps to be advised over phone)

d. In MySQL - create a database by name "wingtiptoys"
e. Create a table - pet
f. Columns to be added are: id, name and species
g. Add data such as follows:

	1, Dog, Domestic
	2, Cat, Domestic
	3, Fish, Domestic


2. Install Postman

3. In Eclipse - build the application and Run (more detailed steps to be given over phone)

4. In Postman send a GET statement to 

http://localhost:8080/pets

5. You should see output as follows:

[{"id": 1, "name": "Dog", "species": "Domestic"},{"id": 2, "name": "Cat", "species": "Domestic"},{"id": 3, "name": "Fish", "species": "Domestic"}]