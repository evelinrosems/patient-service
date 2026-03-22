Patient Service Application

This project is a Spring Boot–based microservice that manages patient data. It provides secure storage and retrieval of patient information using REST APIs. The service is designed with basic security, encryption, and database integration.

Project Overview

The Patient Service allows users to Create, Read, Update, and Delete (CRUD) patient records. It uses Spring Boot for backend development and Spring Data JPA for database operations. Security is handled through configuration classes, and sensitive data is protected using encryption utilities.

Features

Patient Management: Create, Update, Delete, and View patient details
RESTful API Endpoints for easy integration
Spring Boot–based Microservice Architecture
Data Persistence using JPA Repository
Basic Security Configuration implemented
Encryption Support using AES Utility
SSL Configuration using Keystore

Project Structure

Controller: Contains REST API endpoints for patient operations
Model: Contains Patient entity class
Repository: Handles database interaction using JPA
Config: Includes Security Configuration
Util: Contains Encryption Utility class
Resources: Contains application properties and Keystore file

Technologies Used

Java
Spring Boot
Spring Web
Spring Data JPA
Maven
H2 or Relational Database
AES Encryption

How to Run the Project

Clone the repository
Open the project in any IDE such as IntelliJ or Eclipse
Ensure Java and Maven are installed
Run the main class PatientServiceApplication
The application will start on the default port

API Endpoints

POST /patients to create a new patient
GET /patients to fetch all patients
GET /patients/{id} to fetch a specific patient
PUT /patients/{id} to update patient details
DELETE /patients/{id} to delete a patient

Security

The application includes basic security configuration
Data encryption is handled using AES Utility
SSL is enabled using a Keystore file

Configuration

The application.properties file contains database and server configuration
The Keystore file is used for SSL setup

Future Improvements

Add Authentication and Authorization using JWT
Connect to external databases such as MySQL or PostgreSQL
Add validation and exception handling
Implement a Service Layer for better architecture
Integrate with other microservices
