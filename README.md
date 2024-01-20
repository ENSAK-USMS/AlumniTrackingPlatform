# AlumniTrackingPlatform


A platform designed to track and manage the graduation-related activities, including diploma notification, data verification, professional insertion information collection, diploma retrieval scheduling, and administrative operations for the academic service department.

## Project Overview

The platform consists of two main spaces:

1. **Espace Service Scolarité:** This space is dedicated to the administrative staff responsible for managing diploma-related operations.

2. **Espace Lauréat:** This space is designed for graduates, providing them with features like diploma notification, data verification, and document download.

## Objectives

1. **Notification and Diploma Retrieval for Graduates:**
   - Notify graduates about the availability of their diplomas.
   - Allow graduates to verify and provide feedback on the accuracy of their personal data.
   - Implement an electronic signature process before enabling diploma downloads.

2. **Professional Insertion Information Collection:**
   - Collect information about the professional insertion of graduates, including current employment status and career paths.

3. **Diploma Retrieval Scheduling:**
   - Enable graduates to schedule appointments for retrieving physical copies of their diplomas.

4. **Administrative Operations for Academic Service:**
   - Provide academic service personnel with the ability to manage operations, such as handling complaints and maintaining statistics.

## Architecture

### Frontend (Angular)

#### Modules

- Separate modules for the academic service and graduate spaces.

#### Components

- Components dedicated to each functionality, such as diploma notifications, appointment scheduling, etc.

#### Services

- Services for communication with the backend, including data collection for professional insertion.

#### User Interface (UI)

- User-friendly interfaces for graduates to verify and download their diplomas and for academic service personnel to perform administrative operations.

### Backend (Spring Boot)

#### Project Structure

- Logical organization of the project into packages, including controllers, services, and database access.

#### Controllers

- Controllers to manage HTTP requests, including diploma notifications, professional data collection, etc.

#### Services

- Implementation of services for business logic, such as appointment scheduling and complaint handling.

#### Database

- Integration of a database to store information about graduates, diplomas, and professional insertion data.

## Security and Authentication

1. **Authentication:**
   - Implementation of a secure authentication system for graduates and academic service personnel.

2. **Authorization:**
   - Management of permissions based on roles, allowing academic service personnel access to specific functionalities.







## Getting Started

### Prerequisites

- Node.js and npm for Angular development.
- Java and Maven for Spring Boot development.
- Database (e.g., MySQL, PostgreSQL) for backend data storage.

### Installation

1. Clone the repository.
2. Set up frontend and backend dependencies.
3. Configure the database connection.
4. Run the application

## License

This project is licensed under the Apache 2 - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Nothing Yet
