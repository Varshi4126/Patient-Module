# Hospital Management System - Patient Module

## Overview
The Patient Module is a core component of a comprehensive Hospital Management System (HMS). It provides essential features for patients, enabling secure interactions with the hospital's resources, including:

- **Secure registration and login** with form validation, password hashing, and JWT tokenization.
- **Doctor browsing and appointment booking** with specialized doctors.
- **Management of personal information and medical history**.
- **Viewing booked appointments**.

The project consists of three main modules:
1. **Frontend**: Patient-facing user interface developed in React.
2. **Admin Dashboard**: A management dashboard for hospital staff, also built in React.
3. **Backend**: API server developed with Node.js to handle authentication, data processing, and integration.

## Prerequisites
Ensure the following dependencies are installed:
- **Node.js** (version 14 or higher)
- **npm** (version 6 or higher)

## Getting Started
Follow these steps to set up the project locally.

### Clone the Repository
```bash
git clone https://github.com/your-username/hospital-management-system.git
```

### Navigate to the Project Directory
```bash
cd hospital-management-system
```

### Install Dependencies
Install the necessary dependencies for each module.

#### Frontend
```bash
cd frontend
npm install
```

#### Admin Dashboard
```bash
cd ../admin
npm install
```

#### Backend
```bash
cd ../backend
npm install
```

### Start the Development Servers
To run the application locally, start the development servers for each module.

#### Frontend
```bash
cd frontend
npm run dev
```
The frontend will run on [http://localhost:5173](http://localhost:5173).

#### Admin Dashboard
```bash
cd ../admin
npm run dev
```
The admin dashboard will run on [http://localhost:5174](http://localhost:5174).

#### Backend
```bash
cd ../backend
npm run server
```
The backend API server will run on [http://localhost:5000](http://localhost:5000).

## Project Structure

The project is organized into three main directories:
- **Frontend**: Contains the React-based interface for patient-facing features:
  - Registration and login
  - Viewing top doctors and their information
  - Selecting a doctor specialty and booking appointments
  - Managing personal information and medical history

- **Admin Dashboard**: The React-based admin interface for hospital data management:
  - Doctor profile maintenance
  - Appointment schedule management
  - Patient data monitoring

- **Backend**: Node.js-based API server that performs the following tasks:
  - User authentication with JWT
  - Password hashing and form validation
  - CRUD operations for patient, doctor, and appointment data
  - Integration with the frontend and admin dashboard

## Key Features

- **Secure Registration and Login**: Authenticates users with JWT, with passwords securely hashed.
- **Form Validation**: Ensures data integrity and security through comprehensive input validation.
- **Doctor Information**: Allows patients to view detailed doctor information, including specialties and availability.
- **Appointment Booking**: Patients can select a doctor, choose a date and time slot, and book an appointment. Booked appointments are viewable in the "My Appointments" section.
- **Personal Information & Medical History**: Patients can manage their personal information and maintain medical history records.
- **Admin Dashboard**: Enables hospital staff to manage doctor profiles, appointments, and patient records through a user-friendly interface.

## Technologies Used

- **Frontend**: React, React Router, Tailwind CSS, Mermaid (for diagrams)
- **Admin Dashboard**: React, React Router, Tailwind CSS, Recharts (for data visualization)
- **Backend**: Node.js, Express, MongoDB, JWT, bcrypt (for password hashing)

## Contributing
If you are interested in contributing, please follow these steps:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bug fix.
3. **Commit your changes** with clear and descriptive commit messages.
4. **Push your changes** to your forked repository.
5. **Submit a pull request** to the main repository.

---

Thank you for your interest in contributing to the Hospital Management System - Patient Module!
```
