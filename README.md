# LoginAppWithDB

Java Swing project built using NetBeans IDE that connects to MySQL using JDBC.

## Structure
- `src/loginapp/DatabaseConnection.java`: JDBC connection to MySQL
- `lib/`: Place your MySQL Connector/J `.jar` file here
- GUI (JFrame for Homepage) should be added using NetBeans Design View

## Setup
1. Download and install NetBeans + Java JDK + MySQL Server.
2. Add MySQL JDBC driver `.jar` to the `lib` folder and attach it in NetBeans:
   - Right-click `Libraries` > `Add JAR/Folder` > select `.jar` in `/lib`.
3. Replace DB credentials in `DatabaseConnection.java`:
   - `your_database_name`, `your_mysql_username`, `your_mysql_password`.
4. Right-click `DatabaseConnection.java` > Run File to test.

## Homepage GUI
- Create a new JFrame named `Homepage.java` in `src/loginapp`
- Add components: Title, Greeting, Buttons (`View Profile`, `Settings`, `Logout`)
- Use `GroupLayout` for proper layout
- Add logout button logic to switch back to `LoginForm`

---

✅ Ready to expand with login authentication and database operations.
