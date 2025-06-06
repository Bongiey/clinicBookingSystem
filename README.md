# clinicBookingSystem

# Clinic Booking System Database

## Description
This project implements a MySQL database for a Clinic Booking System. It manages patients, doctors, departments, appointments, and medical records with proper relational structure. The database includes:
- Patients and Doctors management
- Department assignments for doctors
- Appointment scheduling with no double-booking constraints
- Medical records linked to appointments
- Appropriate constraints (PK, FK, NOT NULL, UNIQUE) and relationships (1-1, 1-M, M-M)

## Setup and Installation
1. **Prerequisites**: Ensure MySQL is installed on your system.
2. **Create Database**:
   ```sql
   CREATE DATABASE clinic_booking_system;
   USE clinic_booking_sysem;
   ```
3. **Import SQL File**:
   - Save the `clinic_booking_system.sql` file 
   - Run the SQL file using MySQL:
     ```bash
     mysql -u your_username -p clinic_booking < clinic_booking_system.sql
     ```
     Replace `your_username` with your MySQL username and enter your password when prompted.
4. **Verify Setup**:
   - Connect to MySQL and check the database:
     ```sql
     SHOW TABLES;
     ```
   - You should see tables: Patients, Doctors, Departments, Doctor_Departments, Appointments, Medical_Records.


