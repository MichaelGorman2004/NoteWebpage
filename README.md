# Flask Notes Web Application

This Flask-based web application allows users to create an account, log in, and save notes within their account. It utilizes SQLAlchemy as an Object-Relational Mapping (ORM) tool to interact with a database and store user account information and notes.

## Features

The web application provides the following features:

1. **Account Creation**: Users can create a new account by providing a username and password.
2. **Account Login**: Existing users can log in to their account using their username and password.
3. **Note Creation**: Logged-in users can create new notes and associate them with their account.
4. **Note Viewing**: Users can view their existing notes in a list format.
5. **Note Editing**: Users can edit and update their notes.
6. **Note Deletion**: Users can delete their notes when no longer needed.
7. **Account Logout**: Users can log out of their account to end their session.

## Requirements

To run the web application, you need the following:

- Python installed on your system.
- Flask and SQLAlchemy Python packages installed.
- A modern web browser.

## Usage

1. Ensure you have Python 3.x installed on your system.
2. Download the code and save it to your local machine.
3. Open a terminal or command prompt and navigate to the directory where the code is located.
4. Install the required Python packages using the following command:

   ```bash
   pip install flask sqlalchemy
   ```

5. Set up the database by running the following commands:

   ```bash
   python
   >>> from app import db
   >>> db.create_all()
   >>> exit()
   ```

6. Run the web application using the following command:

   ```bash
   python app.py
   ```

7. Open your web browser and visit the localhost 
8. Follow the on-screen instructions to create an account, log in, and manage your notes.

## Customization

If you want to customize the web application, you can modify the following parts:

- **User Interface**: Modify the HTML templates in the `templates/` directory to change the appearance and layout of the web pages.
- **Database Model**: Update the `User` and `Note` classes in the `app.py` file to add or modify fields in the database.
- **Routes and Logic**: Modify the routes and logic in the `app.py` file to implement additional features or customize existing functionality.

## Dependencies

The web application relies on the following Python packages:

- [Flask](https://flask.palletsprojects.com/): A micro web framework for building web applications in Python.
- [SQLAlchemy](https://www.sqlalchemy.org/): An ORM tool that provides an interface to interact with databases.

Ensure that you have these packages installed before running the application.

## License

This web application is released under the [MIT License](LICENSE.md). Feel free to use, modify, and distribute it as per the terms of the license.

## Contributing

If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

## Credits

This web application was created by Michael Gorman. Special thanks to the Flask and SQLAlchemy communities for their contributions to the Python ecosystem.
