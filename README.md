
# CRUD Using PHP and MySQL

This project is a simple CRUD (Create, Read, Update, Delete) application built with PHP and MySQL. It allows users to manage user records, including creating new users, reading user information, updating existing user details, and deleting users.

## Features

- User authentication (login/logout)
- Display user profile and other users' information
- Create new user records
- Update existing user records
- Delete user records

## Prerequisites

- XAMPP (or any local server setup that includes PHP and MySQL)
- Git (optional, for version control)
- Composer (optional, for managing dependencies)

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/itz-mehraz/CRUD_Using_PHP_Mysql.git
   ```

2. **Navigate to the project directory:**

   ```sh
   cd CRUD_Using_PHP_Mysql
   ```

3. **Start your local server (XAMPP):**
   - Make sure Apache and MySQL are running.

4. **Create a database:**
   - Open phpMyAdmin.
   - Create a new database named `crud`.

5. **Import the database:**
   - Import the SQL file provided in the project (`db/crud.sql`) into the `crud` database.

6. **Configure the database connection:**
   - Open `db/config.php`.
   - Update the database connection details (host, username, password, database name) if necessary.

## Usage

1. **Open the application:**
   - Open your web browser.
   - Go to `http://localhost/CRUD_Using_PHP_Mysql` (or the appropriate URL based on your local server setup).

2. **Login:**
   - Use the login credentials to access the application. (Default credentials can be set in the database).

3. **Manage Users:**
   - You can create, read, update, and delete user records.

## File Structure

- `index.php`: Main entry point of the application.
- `login.php`: Login page.
- `logout.php`: Logout functionality.
- `show.php`: Display user details.
- `edit.php`: Update user details.
- `delete.php`: Delete user record.
- `db/config.php`: Database configuration file.
- `css/style.css`: Custom styles for the application.
- `README.md`: Project documentation.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Bootstrap](https://getbootstrap.com/) for styling.
- [FontAwesome](https://fontawesome.com/) for icons.

