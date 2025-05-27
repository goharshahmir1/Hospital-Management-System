# Hospital-Management-System

Prerequisites

* Java JDK 8 or higher
* MySQL Server
* NetBeans or IntelliJ IDE (or any Java IDE)
* MySQL Connector/J (JDBC driver)

### Installation Steps

1. *Clone the Repository*

   bash
   git clone https://github.com/yourusername/Hospital-Management-System-Java.git
   cd Hospital-Management-System-Java
   

2. *Set up the MySQL Database*

   * Create a new database (e.g., hospital_db).
   * Import the SQL script from the /database folder to create tables and seed initial data.

3. *Configure DB Connection*

   * Open the project in your IDE.
   * Locate the DB connection file (e.g., DBConnection.java) and update the following:

     java
     String url = "jdbc:mysql://localhost:3306/hospital_db";
     String username = "your_db_username";
     String password = "your_db_password";
     

4. *Build and Run the Project*

   * Run the main file (e.g., Main.java) to start the application.
   * Log in using test credentials or create new accounts via the admin panel.
