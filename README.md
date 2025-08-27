Car Rental System – 

Project Description

The Car Rental System is a software application designed to manage and streamline the process of renting cars to customers in an efficient and secure manner. The system helps rental agencies keep track of available cars, customer details, booking records, and payments, ensuring smooth operations and improved customer experience.

Key Features:
1. Car Registration
Stores details such as car ID, model, type (SUV, Sedan, Hatchback), seating capacity, daily rent, and availability status.

2. Unique Car & Customer ID Generation
Each car and customer is assigned a unique ID for quick identification.

3. Booking Management
Staff can create rental bookings by linking a customer to an available car, specifying rental duration, and calculating charges.

4. Database Management
All details (cars, customers, bookings, payments) are stored in a database (e.g., MySQL) for easy access and updates.

5. Search & Retrieval
Staff can search cars by model, ID, or availability and retrieve customer/booking details using customer ID or phone number.

6. Update & Delete
Allows modification of customer/car details or cancellation of bookings when required.

7. User Authentication
Only authorized staff/admins can access the system to ensure data integrity and security.

Objective:

To automate the traditional car rental process.

To minimize paperwork and reduce human errors.

To make car booking and tracking faster, more reliable, and customer-friendly.

To ensure secure handling of customer and rental data.

Use Case Example:

A customer visits the rental office → Staff enters customer details → Staff selects an available car → The system generates a unique booking ID → Car availability status is updated → When the customer returns the car, staff retrieves booking details, calculates total rent, and updates the database.

OOPs Concepts Used:

Class & Objects → Car, Customer, Booking, RentalSystem.

Encapsulation → Private fields for car/customer details with getters & setters.

Inheritance → Person → Customer / Staff.

Polymorphism → Method overloading (bookCar, searchCar), method overriding (display details).

Abstraction → Interfaces for rental operations (e.g., IBooking, IPayment).
