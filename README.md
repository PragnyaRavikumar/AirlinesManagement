# Airlines Management System

## Overview

The **Airlines Management System** is a software solution developed to demonstrate **CRUD (Create, Read, Update, Delete)** operations in the context of an airline's day-to-day operations. The system allows users to manage flights, passengers, and bookings effectively. The project utilizes **Streamlit** for a user-friendly frontend, **Python** for the backend, and **SQL** for database management.

This project is focused on showcasing the ability to perform basic CRUD operations efficiently.

## Features

- **Flight Management**: Allows the admin to **add**, **update**, and **delete** flights, and view available flights.
- **Passenger Management**: Admin can **view**, **add**, and **update** passenger information.
- **Booking System**: Passengers can **create** new bookings, **view** their booking history, and **cancel** existing bookings.
- **Ticket Management**: Admin can manage tickets and assign them to passengers.
- **Search Functionality**: Allows users to search for flights based on destination, date, and available seats.

## Technologies Used

- **Python**: Used for backend logic and handling CRUD operations.
- **Streamlit**: Used to create the interactive frontend user interface.
- **SQL**: Used for database management and storing user, flight, and booking information.
- **SQLite**: Lightweight database used in the project for storing records.

## Database Overview

The database consists of several tables to manage different aspects of the airlines' operations:

- **AIRPORT**: Stores information about airports including their name, location, and number of terminals.
- **PAYMENT**: Manages payment details for bookings, including payment status and method.
- **PASSENGER**: Stores passenger details such as personal information and passport number.
- **AIRLINE**: Contains information about airlines including their name and country.
- **BOOKING**: Manages booking details such as the booking status, amount, and the associated passenger and payment.
- **FLIGHT**: Stores details about flights, including flight number, departure and arrival information.
- **TICKET**: Links passengers to booked tickets and manages ticket details such as seat number, flight, and class.
- **USERS**: Stores login credentials for system users (admin).

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/airlines-management-system.git
    ```

2. Navigate to the project folder:

    ```bash
    cd airlines-management-system
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Set up the database (if not already done):

    ```bash
    python setup_database.py
    ```

5. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

## Usage

1. **Admin**: Use the admin panel to manage flights, passengers, bookings, and tickets with CRUD functionalities.
2. **Passenger**: Search for available flights, book tickets, and manage bookings.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
