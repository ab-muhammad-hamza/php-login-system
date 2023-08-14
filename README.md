# Simple PHP login system
This GitHub repository showcases a straightforward PHP login system integrated with sessions. With a focus on simplicity and security, this project provides a foundational example of how to implement user authentication and session management in PHP applications. Whether you're new to PHP development or looking to enhance your understanding of authentication mechanisms, this repository serves as a practical reference for creating a reliable login system using sessions. Explore the code and learn how to securely manage user logins and sessions in your web applications.

# How to use

1. **Installing XAMPP:**
   - Download XAMPP from the official website (https://www.apachefriends.org/index.html) based on your operating system (Windows, macOS, Linux).
   - Run the installer and follow the on-screen instructions to install XAMPP.

2. **Starting XAMPP:**
   - Once installed, open the XAMPP control panel.
   - Start the Apache and MySQL modules by clicking the "Start" button next to each module. This will start the web server and the database server.

3. **Accessing phpMyAdmin:**
   - Open your web browser and navigate to http://localhost/phpmyadmin/
   - You'll be taken to the phpMyAdmin login page.

4. **Creating a Database:**
   - On the phpMyAdmin login page, enter your MySQL username and password (by default, these are both "root").
   - Click on the "Databases" tab in the top navigation.
   - Enter a name for your new database in the "Create database" field.
   - Select "utf8_general_ci" as the collation.
   - Click the "Create" button to create the new database.

5. **Importing "users.sql" File:**
   - Locate the "users.sql" file on your local machine. Make sure it contains the SQL queries needed to create the users table.
   - In phpMyAdmin, select the database you created in step 4 from the left sidebar.
   - Click on the "Import" tab in the top navigation.
   - Click the "Choose File" button and select the "users.sql" file.
   - Leave the other settings as default unless you have specific requirements.
   - Click the "Go" button to import the SQL file and create the users table.

By following these steps, you'll have XAMPP installed, running, a database created, and the "users.sql" file imported into phpMyAdmin. This will set up the environment for your PHP login system.
Once thats done create a folder and clone this repository.

To clone this repository, use the following command:

```
git clone https://github.com/ab-muhammad-hamza/php-login-system.git
```

## Conneceting to Database

1. **Changing Database Credentials:**

   To configure the database connection for the PHP login system, follow these steps:

   - Navigate to the root folder of the PHP login system project.
   - Locate the `config` folder and open the `config.php` file in a text editor.

2. **Edit Database Settings:**

   Inside the `config.php` file, you'll find the following lines:

   ```php
   define('DB_SERVER', 'localhost');
   define('DB_USERNAME', 'root');
   define('DB_PASSWORD', '');
   define('DB_NAME', 'loginSystem');
   ```

   - **DB_SERVER:** This should usually be set to `'localhost'`, but if your database server is hosted on a different server, update it accordingly.
   - **DB_USERNAME:** Set this to your MySQL database username.
   - **DB_PASSWORD:** Set this to your MySQL database password.
   - **DB_NAME:** This is the name of the database you created to store login system data.

3. **Save Changes:**

   After making the necessary changes, save the `config.php` file.

4. **Check Database Connection:**

   - Once you've updated the database credentials, the PHP login system will use these new credentials to connect to your MySQL database.
   - If the credentials are correct and the database server is running, the connection will be established. If not, you'll see an error message.

Remember to keep your database credentials safe and do not share them openly in your code repositories. Always use environment variables or other secure methods to manage sensitive information in production environments.


<div align="center">
  <h2>:tada: Happy Coding! :tada:</h2>
</div>
