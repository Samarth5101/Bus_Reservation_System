![Banner](https://github.com/Samarth5101/Bus_Reservation_System/blob/c055d8ddb68e5e93a12bad33051d2d7626e43b2b/banner.jpg)


# Bus Reservation System

This project is a **Cloud-Based Bus Reservation System** that allows users to book bus tickets online. It provides functionalities for searching available buses, booking tickets, managing bookings, and handling payment transactions. The system is developed using Django and can be deployed in a cloud environment for scalability.

## Features

- **User Registration and Authentication**: Users can sign up, log in, and manage their accounts.
- **Bus Search and Booking**: Users can search for buses, view available seats, and book tickets.
- **Booking Management**: Users can view and manage their existing bookings.
- **Admin Panel**: Admins can manage buses, routes, and monitor bookings.
- **Responsive Design**: The user interface is designed to be responsive for mobile, tablet, and desktop users.

## Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript (Django templates)
- **Database**: SQLite (can be replaced with PostgreSQL or MySQL)
- **Version Control**: Git and GitHub

## Installation

To run this project locally, follow the steps below:

1. Clone the repository:
   ```bash
   git clone https://github.com/Samarth5101/Bus_Reservation_System.git

2. Navigate to the project directory:
   ```bash
   cd Bus_Reservation_System

3. Set up the virtual environment:
   ```bash
   python -m venv myenv

4. Activate the virtual environment:
   * On Windows:
     ```bash
     myenv\Scripts\activate
     
   * On macOS/Linux:
     ```bash
     source myenv/bin/activate

5. Install the dependencies:
   ```bash
   pip install -r requirements.txt

6. Run migrations to set up the database:
   ```bash
   python manage.py migrate

7. Start the development server:
   ```bash
   python manage.py runserver

8. Access the application by visiting http://127.0.0.1:8000/ in your browser.

## Usage

* Register for an account or log in using existing credentials.
* Search for available buses based on your route and travel date.
* Select the bus and proceed with booking.
* Manage your bookings from the user dashboard.

## Folder Structure

* **myapp/**: Contains the main application logic, including models, views, and templates.
* **myproject/**: Contains project settings and configurations.
* **static/**: Contains static assets like CSS and images.
* **templates/**: Contains HTML templates for the frontend.
* **db.sqlite3**: The default SQLite database file (can be replaced for production).

## Contact

For any queries or issues, feel free to reach out at: [samarth.mishra373@example.com](mailto:samarth.mishra373@example.com)
