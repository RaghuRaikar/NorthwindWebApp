Northwind Web App
=================
A **dynamic web application** that interacts with the **Northwind database**, specifically managing customer data using an **object-oriented approach**.

Features
--------
-   **Customer Data Management**: Implements **DAO (Data Access Object) patterns** to interact with customer records.
-   **Database Connectivity**: Uses `DatabaseConnectionManager` to handle connections efficiently.
-   **Modular OOP Design**: Organized into separate classes for better maintainability.

Project Structure
-----------------
'''
📦northwindwebapp
 ┗ 📂target
 ┃ ┣ 📂classes
 ┃ ┃ ┗ 📂com
 ┃ ┃ ┃ ┗ 📂rr
 ┃ ┃ ┃ ┃ ┣ 📂customers
 ┃ ┃ ┃ ┃ ┃ ┣ 📜CustomersDAO.class
 ┃ ┃ ┃ ┃ ┃ ┗ 📜customers.class
 ┃ ┃ ┃ ┃ ┗ 📂northwind
 ┃ ┃ ┃ ┃ ┃ ┗ 📜DatabaseConnectionManager.class
 ┃ ┗ 📜northwindwebapp-1.0-SNAPSHOT.war
'''
-   **`CustomersDAO.class`**: Handles database operations related to customers.
-   **`customers.class`**: Represents customer entities in an object-oriented way.
-   **`DatabaseConnectionManager.class`**: Manages and optimizes database connections.

Setup & Usage
-------------
1.  Clone the repository:

    `git clone https://github.com/RaghuRaikar/NorthwindWebApp.git`

2.  Ensure you have **Java** and **a compatible database (e.g., MySQL, PostgreSQL)** installed.
3.  Run the application:

    `java -jar northwindwebapp-1.0-SNAPSHOT.jar`

4.  The app will establish a connection to the **Northwind database** and allow interactions with customer data.

Future Enhancements
-------------------
-   Implement **CRUD operations** via a RESTful API.
-   Add **frontend integration** for user-friendly customer management.
-   Optimize database queries for **faster performance**.

Contributing
------------
Contributions are welcome! Feel free to submit a pull request or open an issue.
