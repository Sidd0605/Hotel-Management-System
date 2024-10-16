# Hotel-Management-System using Python and MYSQL

Hotel Management System
This project is a Hotel Management System created using Python and Tkinter for the graphical user interface. It allows the user to choose between two roles: Manager and Customer. Based on the role selected, different features and functionalities are available.

Features
Manager Login:
Access to manage rooms, bookings, and customer information.

Customer Interface:
Customers can check room availability, book rooms, and update personal details.

Database:
All customer and room information is stored in a MySQL database.
The SQL queries and database schema are provided in the sql.txt file.

Getting Started
Prerequisites
Python 3.x installed on your machine.
Tkinter (usually included with Python installations).
MySQL database server installed and running.
Python packages: mysql-connector-python for connecting to the MySQL database.

To install the MySQL connector, run:
pip install mysql-connector-python

Database Setup
Open sql.txt file located in the project directory.
Run the SQL commands in the file to create the required database and tables.
Ensure your MySQL server is running.
Running the Application
Clone this repository or download the files.

Ensure all the files including the sql.txt file are in place.

Run the main Python file to start the application:

python main.py
When prompted, choose whether you are a Manager or a Customer.

Manager Login Details
Username: manager
Password: 12345
If you select the Manager option, you will be required to enter the above credentials to proceed.

Customer Options
Customers can view available rooms, make bookings, and update their personal details.

Technologies Used
Python: For backend logic.
Tkinter: For creating the graphical user interface.
MySQL: For storing hotel, room, and customer data.

Future Improvements
Adding additional features like payment processing.
Implementing advanced customer queries and room management.
Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. All contributions are welcome!

License
This project is licensed under the MIT License.


