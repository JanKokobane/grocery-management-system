
# Grocery Management System

The Grocery Management System is a web application that allows users to add, sell, update, delete, and manage grocery store items. The application is built using HTML, CSS, JavaScript, Python, and Flask. MySQL is used as the database for storing and managing data.

## Features

- Add new grocery items
- Sell grocery items
- Update existing grocery items
- Delete grocery items
- Manage store inventory

## Technologies Used

- HTML
- CSS
- JavaScript
- Python
- Flask
- MySQL

## Installation

### Prerequisites

- Python 3.6 or higher
- MySQL

### Setup

Clone the repository:
   ```bash
   git clone https://github.com/yourusername/grocery-management-system.git

Create a virtual environment:

bash
python -m venv venv
Activate the virtual environment:

On Windows:
venv\Scripts\activate
On macOS and Linux:
source venv/bin/activate

Install the dependencies:

pip install -r requirements.txt
Set up the database:

Create a MySQL database named grocery_store.

Run the SQL script provided in the db_setup.sql file to set up the tables.

Configure the database connection:

Update the sql_connection.py file with your MySQL database credentials.

Run the Flask application:
