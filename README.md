# AirBnB_clone_v2

AirBnB Clone v2 is an updated version of the popular AirBnB Clone repository.
The repository is designed to mimic the functionality of the Airbnb website by
providing a command-line interface for users to search for, view, and book properties.

Features
AirBnB Clone v2 comes with several features, including:

A robust command-line interface for managing properties and bookings
Support for multiple users and user authentication
Integration with a PostgreSQL database to store property and user data
Ability to search and filter properties by location, price, and other parameters
Support for creating and managing bookings
Detailed property information, including photos, amenities, and availability calendars
Installation
To use AirBnB Clone v2, you will need to have Python 3.x and PostgreSQL installed on your system.
Once you have those dependencies installed, you can install the repository by cloning the repository
to your local machine:

bash
git clone https://github.com/erc-net/AirBnB_clone_v2.git
After cloning the repository, you will need to create a Python virtual environment and install the
project dependencies:

bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
Once you have installed the dependencies, you can set up the database by running the following commands:

bash
flask db init
flask db migrate
flask db upgrade
Finally, you can start the application by running the following command:

bash
python3 console.py
Usage
AirBnB Clone v2 provides a command-line interface for managing properties and bookings.
Once you have started the application, you can use the following commands to interact with the
application:

create <class>: Create a new instance of a class (e.g., Property or User)
show <class> <id>: Display the details of an instance of a class
destroy <class> <id>: Delete an instance of a class
all <class>: Display all instances of a class
update <class> <id> <attribute_name> "<attribute_value>": Update an instance of a class with a new
attribute value
For example, to create a new property, you can run the following command:

bash
(create) Property
You will then be prompted to enter the property details, such as the property name, location, and price.

Contributing
If you would like to contribute to AirBnB Clone v2, you can do so by submitting a pull request to the
repository. Before submitting a pull request, please make sure that your changes have been thoroughly
tested and that they adhere to the project's coding standards.

Credits
AirBnB Clone v2 was originally developed by <a href="https://github.com/GabrielAbdul">Gabriel Abdul</a>
and <a href="https://github.com/edward0rtiz">Edward Ortiz</a>. The project was later updated and modified by
<a href="https://github.com/erc-net"><b>Eric Taruwinga</b></a> and Mondliwethu Vundla.
