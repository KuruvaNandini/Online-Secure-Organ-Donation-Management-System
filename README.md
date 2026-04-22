The Online Secure Organ Donation Management System is a web-based application designed to digitize and streamline the process of organ donation and transplantation. The main objective of this project is to provide a secure, transparent, and efficient platform that connects donors, patients, and hospitals in a single system.

In traditional organ donation processes, maintaining records manually and finding suitable donors for patients can be time-consuming and error-prone. This project addresses those challenges by automating the workflow and ensuring faster donor–patient matching.

The system allows users to register either as a donor or a patient. Donors can provide details such as personal information, blood group, available organ type, and donation status. Patients can register their organ requirements along with urgency levels such as low, medium, or high priority.

A dedicated matching module is included to link donors with patients based on the required organ and availability status. Once a successful match is found, the system stores the donation details, including hospital information, donation date, and final status.

The project is developed using:

Java for core application logic
Spring Boot for building RESTful APIs and backend services
Hibernate (JPA) for ORM-based database management
JDBC for optimized custom SQL queries
MySQL as the relational database

This hybrid approach combines the simplicity of Hibernate with the flexibility of JDBC for complex queries.

The system is designed with a well-structured database that includes entities such as:

User
Donor
Patient
Organ
Match
Donation
Hospital

This project demonstrates practical implementation of database relationships, secure data management, and scalable backend architecture, making it a strong real-world application project.

The ultimate goal of this system is to reduce delays in organ allocation, improve transparency, and contribute to saving lives through technology.
