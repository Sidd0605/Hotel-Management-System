# Hotel-Management-System using Python and MYSQL

This project is a Hotel Management System created using Python and Tkinter for the graphical user interface. It allows the user to choose between two roles: Manager and Customer. Based on the role selected, different features and functionalities are available.

## Features

1) Manager Interface(similar to customer interface but with additional features:
      Access to manage rooms, bookings, and customer information.


2) Customer Interface:
      Customers can check room availability, book rooms, and update personal details.


3) Database:
    All customer and room information is stored in a MySQL database.
    The SQL queries and database schema are provided in the sql.txt file.


## Prerequisites

   1) Python 3.x installed on your machine.
   2) Tkinter (usually included with Python installations).
   3) MySQL database server installed and running.
   4) Python packages: mysql-connector-python for connecting to the MySQL database.
      

To install the MySQL connector, run:
pip install mysql-connector-python

## Database Setup
   1) Open sql.txt file located in the project directory.
   2) Run the SQL commands in the file to create the required database and tables.
   3) Ensure your MySQL server is running.
   4) Clone this repository or download the files.
   5) Running the Application 

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

## Technologies Used
   1) Python: For backend logic.
   2) Tkinter: For creating the graphical user interface.
   3) MySQL: For storing hotel, room, and customer data.
