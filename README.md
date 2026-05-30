# Student Record Management System
A JavaFX CRUD desktop application connected to a PostgreSQL database. 

(I used Eclipse)
### How to run project:
1. Run the included `database_setup.sql` script in pgAdmin 4 to build the required table.
2. Update the password in `src/application/DBConnection.java` to match your local database.
3. **Required Dependencies:**
   * [JavaFX SDK 21](https://gluonhq.com/products/javafx/)
   * [PostgreSQL JDBC Driver](https://jdbc.postgresql.org/download/)
4. Import the dependencies into your Eclipse Build Path and configure the VM arguments
5. Run `MainApp.java` to start the application!
