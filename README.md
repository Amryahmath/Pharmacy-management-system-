

# Pharmacy Management System

A web-based Pharmacy Management System built with a frontend using HTML, CSS, and JavaScript, and a backend powered by Python and MySQL. This system helps manage the operations of a pharmacy, including inventory management, sales tracking, customer management, and more.

## Features

- **Inventory Management**: Add, update, and delete medicines in the inventory.
- **Sales Tracking**: Record sales transactions and generate sales reports.
- **Customer Management**: Store customer details for easy access and future orders.
- **Data Analytics**: View reports on inventory levels, sales, and more.
- **User Authentication**: Admins can log in securely to manage the system.

## Tech Stack

- **Frontend**: 
  - HTML
  - CSS
  - JavaScript
- **Backend**: 
  - Python (Flask/Django)
- **Database**: 
  - MySQL
- **Tools**: 
  - Visual Studio Code, Sublime Text, or any text editor for coding.
  - MySQL Workbench for database management.

## Setup

To run this project locally, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/Amryahmath/pharmacy-management-system.git
cd pharmacy-management-system
```

### 2. Install Backend Dependencies

Install the necessary Python libraries using pip:

```bash
pip install -r requirements.txt
```

Make sure you have Python 3.x installed.

### 3. Set up the Database

- Create a MySQL database and configure your credentials.
- Import the database schema into MySQL.

Example of creating a database and user:

```sql
CREATE DATABASE pharmacy_db;
CREATE USER 'pharmacy_user'@'localhost' IDENTIFIED BY 'your_password';
GRANT ALL PRIVILEGES ON pharmacy_db.* TO 'pharmacy_user'@'localhost';
```

- Configure the database connection in your backend Python code. Update the database details in the `config.py` (or relevant file).

### 4. Run the Backend

Start the backend server:

```bash
python app.py
```

Your backend will be running on `http://localhost:5000` (or any other port you have configured).

### 5. Run the Frontend

Open the `index.html` file in your browser to interact with the Pharmacy Management System's frontend.

### 6. Access the Application

After setting up the backend and frontend, you can access the application by navigating to the following URL in your browser:

```
http://localhost:5000
```

Log in with the admin credentials and start managing the pharmacy.

## Usage

- **Admin Panel**: Admin users can log in to manage the pharmacy inventory, sales, and customer details.
- **Reports**: Admins can view sales reports and inventory reports.

## Contributing

Feel free to fork this project, submit issues, or make pull requests. Contributions are always welcome!

### Steps to Contribute:
1. Fork the repo.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add feature'`).
5. Push to your branch (`git push origin feature-branch`).
6. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

