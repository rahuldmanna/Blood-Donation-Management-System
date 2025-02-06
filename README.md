# Blood Donation Management Service

An interactive web-based platform developed using PHP, HTML, CSS, and JavaScript that streamlines the blood donation process. This system connects patients, donors, and administrators, enabling efficient blood request management, real-time inventory monitoring, and seamless donation tracking.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [Database Setup](#database-setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Authors and Acknowledgements](#authors-and-acknowledgements)

## Overview

The **Blood Donation Management Service** is designed to simplify and optimize the blood donation process by:
- Allowing **patients** to register, login, and make blood requests.
- Enabling **donors** to register, login, and submit blood donation offers.
- Providing **administrators** with the tools to manage blood requests, update blood stock, and monitor donation activities.

By centralizing these functionalities, the project aims to increase transparency, reduce response times, and ensure that critical blood resources are efficiently allocated.

## Features

- **Patient Module**
  - Signup and Login functionalities.
  - Ability to make blood requests.
  - View request history and status updates.

- **Donor Module**
  - Registration and Login for donors.
  - Submission of blood donation offers.
  - Access to donation history and status information.

- **Admin Module**
  - Secure login for administrators.
  - Manage patient and donor data.
  - Approve or reject blood requests.
  - Real-time tracking of blood inventory and automatic update of blood stock.

- **Database Management**
  - Designed using relational schemas with normalization.
  - Includes complex queries, triggers, and transaction controls.
  - Real-time alerts and warnings for blood stock levels.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Server:** Local development using XAMPP/WAMP or similar

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Avjot-Chawla/Blood-Donation-Management-Service.git
   ```

2. **Place in Web Server Directory:**
   - Copy the project folder into your local server's root directory (e.g., `htdocs` for XAMPP).

3. **Configure Database Connection:**
   - Update the database connection credentials in your PHP files if necessary. By default, the connection uses:
     - **Username:** root
     - **Password:** root
     - **Database Name:** bdms_db

4. **Start Your Server:**
   - Launch your local server (e.g., XAMPP/WAMP) and start Apache and MySQL services.

## Database Setup

1. **Create Database:**
   - Open your MySQL client (phpMyAdmin or MySQL CLI) and create a new database named `bdms_db`.

2. **Run SQL Scripts:**
   - Use the provided DDL and DML queries in the project report to create the necessary tables and populate them with initial data. (See the project report chapters for the complete SQL commands.)

## Usage

1. **Access the Home Page:**
   - Open your browser and navigate to `http://localhost/your_project_folder/Home.html`.

2. **Modules:**
   - **Patients:** Use the “Patient Signup” or “Patient Login” links to access your dashboard where you can request blood and view request history.
   - **Donors:** Use the “Donor Signup” or “Donor Login” links to register or login, then proceed to donate blood or view donation history.
   - **Administrators:** Login via the “Admin Login” page to manage blood requests, update records, and monitor stock levels.

## Project Structure

```
Blood-Donation-Management-Service/
├── BDMS PROGRAM/           # Main directory containing project files
│   ├── Home.html          # Landing page
│   ├── PatientLogin.php   # Patient login page
│   ├── PatientSignup.php  # Patient registration page
│   ├── DonorLogin.php     # Donor login page
│   ├── DonorSignup.php    # Donor registration page
│   ├── AdminLogin.php     # Admin login page
│   └── ...                # Additional PHP, HTML, CSS, JS files for different modules
├── styles/                # CSS files for styling the project pages
├── images/                # Images used in the project
└── README.md              # This file
```

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## Authors and Acknowledgements

- **Rahul Dev Manna** – RA2211003010570
- **Shreyan Dutta** – RA2211003010583
- **Avjot Singh Chawla** – RA2211003010584
- **Project Supervisor:** Dr. Thamizhamuthu R  
  *Department of Computing Technologies, SRM Institute of Science and Technology*

---
