# Voting App

Welcome to the Voting App! This application is built using Spring Boot for the backend and HTML, CSS, and Bootstrap for the frontend. It uses MySQL as the database to store voting data.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

## Introduction

The Voting App is a web application that allows users to create and participate in polls. It is designed to be simple and user-friendly, with a clean and modern interface.

## Features

- Create new polls with multiple options
- Vote on existing polls
- View poll results
- Responsive design with Bootstrap

## Technologies Used

- **Backend:** Spring Boot
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** MySQL

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Java 8 or higher
- Maven
- MySQL

## Installation

To install and run this project locally, follow these steps:

1. **Clone the repository**
    ```sh
    git clone https://github.com/SaGar-hub1/votingapp.git
    cd votingapp
    ```

2. **Set up the database**
    - Create a MySQL database named `votingapp`
    - Update the `application.properties` file with your MySQL username and password
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/votingapp
    spring.datasource.username=yourUsername
    spring.datasource.password=yourPassword
    spring.jpa.hibernate.ddl-auto=update
    ```

3. **Build and run the backend**
    ```sh
    mvn clean install
    mvn spring-boot:run
    ```

4. **Open your browser**
    Navigate to `http://localhost:8080` to access the application.

## Usage

- **Creating a Poll:** Navigate to the "Create Poll" section and fill out the form with your poll question and options.
- **Voting:** View existing polls and select your preferred option to cast your vote.
- **Viewing Results:** Click on a poll to see the voting results.

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Open a Pull Request


## Contact

If you have any questions or suggestions, feel free to reach out:

- **GitHub:** [SaGar-hub1](https://github.com/SaGar-hub1)

---