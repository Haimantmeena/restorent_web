Restaurant Website

Introduction
This project is a restaurant website designed to showcase the restaurant's menu, allow users to make reservations, and provide information about the restaurant's location and contact details. The website is built using HTML, CSS, JavaScript, PHP, and MySQL.

Installation

To run the website locally on your machine, follow these steps:

Clone the Repository:

bash
Copy code

git clone https://github.com/your-username/restaurant-website.git
Set Up the Database:

Ensure you have MySQL installed on your machine.
Create a new MySQL database named restaurant_website.
Import the provided SQL file (restaurant_website.sql) into the newly created database to set up the necessary tables and data.

css

mysql -u your_username -p restaurant_website < restaurant_website.sql
Configure Database Connection:
Navigate to the config directory.
Edit the db_config.php file and update the database connection details (hostname, username, password, and database name) according to your MySQL 

setup.
Usage
Once you have completed the installation steps:

Start the Web Server:
You can use PHP's built-in web server to run the website locally.

php -S localhost:8000
Access the Website:
Open your web browser and navigate to http://localhost:8000 to view the restaurant website.
Features

Menu Display: Display the restaurant's menu with categories and item details.
Reservation System: Allow users to make reservations by providing their contact information and preferred reservation date/time.
Location and Contact Information: Provide information about the restaurant's location, opening hours, and contact details.

Technologies Used
HTML5
CSS3
JavaScript
PHP
MySQL
Contributing

Contributions are welcome! If you would like to contribute to this project, please fork the repository, make your changes, and submit a pull request.

License
This project is licensed under the MIT License.

