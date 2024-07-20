# BuilderStream

The objective of the BuildingStream Owner's Part is to create a user-friendly and efficient platform for property owners to manage their property listings. The application aims to streamline the process of adding, updating, and deleting property information while ensuring secure user authentication and data management.

## Functionality

The BuildingStream Owner's Part application provides the following functionality:

- **Registration**: Property owners can register by providing their personal details, including name, email, phone number, and password. The registration form validates the input data and securely stores the user's information in the database.

- **Login**: Registered owners can log in to the application using their email and password. The login functionality verifies the user's credentials and grants access to the owner's dashboard.

- **Property Addition**: Once logged in, property owners can add their properties by filling in the property details such as location, type, price, and additional information. The application validates the entered data and saves it in the MySQL database.

- **Viewing Added Property**: Property owners can view a list of their added properties on their dashboard. The application retrieves the property data from the database and displays it in a structured manner, allowing owners to easily manage and monitor their property listings.

- **Property Update**: Property owners have the ability to update the details of their added properties. They can modify information such as price, availability, or description through a form provided by the application. The updated data is saved in the database, reflecting the changes in the property listing.

- **Property Deletion**: If property owners decide to remove a property listing, they can delete it from their dashboard. The application deletes the corresponding property data from the database, ensuring the removal of the property from the system.

- **View Profile**: Once logged in, owners can view their profile, which contains their personal information and details related to their properties. The profile may display the owner's name, email, phone number, and other relevant information.

- **Logout**: Property owners can securely log out from the application.

## Prerequisites

- Node.js
- Maven (Installed in Eclipse or IntelliJ or any other IDE)
- MySQL or SQLyog

## Installation Steps

1. **Frontend Setup**
    - Download and open the `React-BuilderStream` folder.
    - In terminal:
      ```sh
      npm install  # for installing react-builderstream dependencies and libraries
      npm start    # to run the application
      ```

2. **Backend Setup**
    - In MySQL, create a Database.
    - Download and open the `Spring-BuilderStream` folder.
    - In Eclipse or IntelliJ:
        - Alter the `pom.xml` file based on your system and Maven compatibility.
        - Open `application.properties` file and provide your Database details.
        - Based on your table, alter the table name in the entities file under the `Entity` folder.
        - Run the application.
