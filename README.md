# Bank Management System (Spring Boot)
Welcome to the Bank Management System repository built using Spring Boot! This project is designed to provide a foundation for managing banking operations using modern web technologies.

## Introduction
The Bank Management System is a web-based application developed using Spring Boot that aims to streamline various banking operations. This system offers features to manage customer accounts and perform transactions.

## Features
- User-Friendly Web Interface: Enjoy a user-friendly web interface designed for both customers, crafted using Angular. Check out the frontend repository on [GitHub](https://github.com/techflow21/springboot-bankapp).
- Authentication and Authorization: We prioritize security by implementing robust user authentication and authorization mechanisms, guaranteeing safe and controlled access to the system.
- Multi-Account Support: Users have the convenience of creating up to three separate accounts within the system, catering to various financial needs and goals.
- Comprehensive Account Details: Customers can easily access a wealth of information about their accounts, including balance summaries, card numbers, CVV numbers, and more. This empowers users with a clear overview of their financial status.
- Efficient Transaction Handling: Our system offers well-defined API endpoints that enable seamless fund transfers between accounts. This ensures efficient and accurate transaction processing.

## Installation

To run the Bank Management System locally, you will need the following:
- Java 17 or higher
- Maven
- PostgreSQL

Once you have the required tools installed, follow these steps to install the Bank Management System:

1. Clone this repository:
    ```shell
       git clone https://github.com/techflow21/springboot-bankapp.git
    ```
2. Edit the database configurations in application.properties file.
3. Navigate to the project directory:
    ```shell
    cd springboot-bankapp
    ```
4. Build and run the application using Maven
    ```shell
    mvn spring-boot:run
    ```
5. Explore the Application: Once the application is up and running, open your web browser and access it at: `http://localhost:8080`
6. Access API Documentation: Additionally, you can explore the API documentation by navigating to: `http://localhost:8080/swagger-ui.html`. This provides detailed insights into the available API endpoints and functionalities.


## Usage

- Customer Actions:
   - Account Creation: As a customer, you have the privilege of creating multiple accounts tailored to your financial needs.
   - View Account Details: Easily access comprehensive details about your accounts, empowering you with insights into your balances and transactions.

- Transaction Operations:
  - Deposit Funds: Any interface can conveniently utilize the `/transaction/deposit` endpoint to securely deposit funds into specified accounts.
  - Withdraw Funds: Similarly, the `/transaction/withdraw` endpoint is available for withdrawing funds from accounts, ensuring your transactions are seamless and accurate.


## Database Schema

## Technologies Used
- Java
- Spring Boot
- Spring Security
- json web token (JWT)
- Spring Data JPA
- Lombok
- PostgreSQL
- Maven 
- Swagger
- Docker


## Contributing
Contributions to the Bank Management System project are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request explaining your changes.
