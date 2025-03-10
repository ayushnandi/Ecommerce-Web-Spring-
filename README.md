# E-Commerce Platform

## Overview
This project is a full-fledged **E-Commerce Platform** built using **Spring Boot** for the backend and **React.js** for the frontend. It provides seamless product management, order processing, and secure user authentication. The platform ensures efficient data handling with **Hibernate** and **PostgreSQL** while leveraging **Maven** for dependency management.

## Features
- **User Authentication & Authorization:** JWT-based role-based authentication for secure access.
- **Product Management:** CRUD operations for products, categories, and inventory.
- **Order Processing:** Secure order placement, tracking, and history management.
- **Admin Dashboard:** Manage users, orders, and product listings efficiently.
- **Shopping Cart System:** Add-to-cart, remove, and checkout functionalities.
- **Secure Payments:** Integration with third-party payment gateways.
- **RESTful APIs:** Efficient API endpoints for data exchange and frontend interaction.

## Technology Stack
### Backend:
- **Spring Boot** (Microservices architecture)
- **Spring JPA** (Data persistence)
- **Hibernate** (ORM for relational data management)
- **PostgreSQL** (Relational database)
- **Maven** (Build automation & dependency management)
- **Lombok** (Reducing boilerplate code)
- **Spring Security & JWT** (Authentication & Authorization)
- **Postman** (API testing & documentation)

### Frontend:
- **React.js** (Frontend development)
- **Redux** (State management)
- **Axios** (API requests handling)
- **Bootstrap & Material UI** (UI components)

## Installation & Setup
### Prerequisites:
- Java 11+
- Node.js & npm
- PostgreSQL
- Maven

### Backend Setup:
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/ecommerce-platform.git
   cd ecommerce-platform/backend
   ```
2. Configure PostgreSQL database in `application.properties`.
3. Install dependencies & build the project:
   ```sh
   mvn clean install
   ```
4. Run the Spring Boot application:
   ```sh
   mvn spring-boot:run
   ```

### Frontend Setup:
1. Navigate to the frontend directory:
   ```sh
   cd ../frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React development server:
   ```sh
   npm run dev
   ```
4. Open `http://localhost:3000` to access the frontend.

## API Documentation
Use **Postman** to test API endpoints. API documentation is available at `/swagger-ui` when the backend is running.

## Contribution
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Added new feature"`).
4. Push the branch (`git push origin feature-name`).
5. Open a pull request.

