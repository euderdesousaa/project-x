# Project-X

## Description
This project is a Twitter-style social network built using the following technologies: Java 17, Spring Boot, MySQL for data storage, RabbitMQ for asynchronous messaging, Docker for containerization, and OAuth2 for authentication.

## Features
- **Create Profile:** Users can create personalized profiles.
- **Create Post:** Post messages to share with other users.
- **Edit and Delete:** Ability to edit or delete posts.
- **Feed:** View a feed of posts from other users.

## API Documentation

The API documentation is available through Swagger. You can explore the API locally or access the hosted version on Render.com.

### Access via Render.com

If you don't want to clone the repository and prefer to access the API directly on Render.com, follow these steps:

1. Open your browser and go to [render](https://api-projectx.onrender.com).

The Swagger interface will provide detailed information about available endpoints, necessary parameters, and examples of requests and responses.

### Local Access

If you prefer to run the application locally, follow the steps below:

1. Make sure the application is running.
2. Open your browser and go to http://localhost:8080/swagger-ui.html.

## Usage
Create a profile.
Log in via Google and explore the features of creating, editing, and deleting posts.
Check the feed to see posts from other users.

## Technologies Used
- **Docker** is a virtualization platform that allows running applications in isolated containers.
- **MySQL** is a relational database management system.
- **Java 17** is the latest version of the Java programming language.
- **Spring** is a Java development framework that facilitates building web applications and microservices.
- **RabbitMQ** is an AMQP messaging server.
- **OAuth2** is an authorization protocol that allows users to share their credentials with third-party applications.
- **Swagger** is a tool that allows documenting REST APIs.

## Installation and Execution
1. Clone this repository.
   ```bash
   git clone https://github.com/euderdesousaa/project-x
   ```
2. Navigate to the project directory.
   ```bash
   cd project-x
   ```
3. Configure environment variables for MySQL, RabbitMQ, and OAuth2.

5. Run the application.
   ```bash
   docker-compose up
   ```
