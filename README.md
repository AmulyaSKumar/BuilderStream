# BuilderStream
The objective of the BuildingStream Owner's Part is to create a user-friendly and efficient platform for property owners to manage their property listings. The application aims to streamline the process of adding, updating, and deleting property information while ensuring secure user authentication and data management.

Functionality:
The BuildingStream Owner's Part application provides the following functionality: 
  Registration: Property owners can register by providing their personal details, including name, email,phone number, and password. The registration form validates the input data and securely stores the user's information in the database. 
  Login: Registered owners can log in to the application using their email and password. The login functionality verifies the user's credentials and grants access to the owner's dashboard. 
  Property Addition: Once logged in, property owners can add their properties by filling in the property details such as location, type, price, and additional information. The application validates the entered data and saves it in the MySQL database. 
  Viewing Added Property: Property owners can view a list of their added properties on their dashboard. The application retrieves the property data from the database and displays it in a structured manner, allowing owners to easily manage and monitor their property listings. 
  Property Update: Property owners have the ability to update the details of their added properties. They can modify information such as price, availability, or description through a form provided by the application. The updated data is saved in the database, reflecting the changes in the property listing. 
  Property Deletion: If property owners decide to remove a property listing, they can delete it from their dashboard. The application deletes the corresponding property data from the database, ensuring the removal of the property from the system. 
  View Profile: Once logged in, owners can view their profile, which contains their personal information and details related to their properties. The profile may display the owner's name, email, phone number, and other relevant information.
  Logout: Property owners can securely log out from the application.

Prerequistes:
Node JS
Maven (InstallIn Eclipse or IntelliJ or any other)
MySQL or SQLyog

Installation Steps:
Download and open the React-BuilderStream folder 
In terminal, npm install ( for installing react-buildersstream dependencies and libraries )
             npm start ( to run the application )

In MySQl, create a Database 
Download and open Spring-BuilderStream folder 
In Eclipse or IntelliJ
  Alter the pom file based on your system and maven compatibility.
  Open application.properties file, alter the feilds by providing your Database details.
  Based on Your Table ,Alter the tablename in entites file under Entity folder .
  Run the application.
  
