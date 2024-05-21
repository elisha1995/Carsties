# Car Auctioning Microservices Web App

Welcome to the Car Auctioning Microservices Web App! This project showcases my skills in building a robust, scalable web application using a microservices architecture with modern technologies. Below is an overview of the project, along with the skills and knowledge I gained through its development.

## Project Overview

This web application allows users to auction cars through a microservices-based architecture. 
The backend is built with .NET 8, and the frontend is developed using Next.js 14. The project leverages Docker for containerization, Identity Server for server-side authentication, RabbitMQ for messaging, and SignalR for Notification.

## Key Features

- **Microservices Architecture:** Separation of concerns into discrete, independently deployable services.
- **Authentication:** Secure user authentication and authorization using Identity Server.
- **Real-Time Communication:** Real-time updates and notifications with SignalR.
- **Asynchronous Messaging:** Reliable message passing between services with RabbitMQ.
- **Containerization:** Consistent development and deployment environments using Docker.

## Skills and Knowledge Gained

### Backend Development with .NET 8

- **Microservices Architecture:** Gained in-depth understanding of designing and implementing a microservices-based architecture, focusing on scalability and maintainability.
- **API Development:** Developed RESTful APIs using ASP.NET Core, following best practices for security, performance, and documentation.
- **Authentication and Authorization:** Implemented secure authentication and authorization mechanisms with Identity Server, managing user roles and permissions effectively.

### Frontend Development with Next.js 14

- **Modern JavaScript/TypeScript:** Applied modern TypeScript features and best practices to build a dynamic user interface.

### Containerization with Docker

- **Docker Basics:** Learned how to containerize applications using Docker, creating Dockerfiles for both the backend and frontend services.
- **Docker Compose:** Used Docker Compose to orchestrate multi-container applications, ensuring seamless integration between services.
- **Environment Management:** Managed different environments (development, staging, production) using Docker, ensuring consistency across the development lifecycle.

### Messaging with RabbitMQ

- **Asynchronous Communication:** Implemented asynchronous messaging between microservices using RabbitMQ, enhancing system reliability and scalability.
- **Message Queues and Topics:** Gained practical experience with message queues, topics, and exchange types, optimizing message routing and processing.
- **Error Handling and Retries:** Developed robust error handling and retry mechanisms for message processing, ensuring fault tolerance.

### Real-Time Communication with SignalR

- **Real-Time Updates:** Integrated SignalR to provide real-time updates and notifications to users, improving the interactivity of the application.

### Additional Skills

- **Unit and Integration Testing:** Wrote comprehensive unit and integration tests to ensure the reliability and correctness of the application.

## How to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/elisha1995/Carsties.git
   cd Carsties
2. Ensure you have Docker Desktop installed on your machine. If not download and install from Docker and review their installation instructions for your Operating system.
3. Build the services locally on your computer by running (NOTE: this may take several minutes to complete):
   ```bash
   docker compose build
4. Once this completes you can use the following to run the services:
   ```bash
   docker compose up -d

![Screenshot (885)](https://github.com/elisha1995/Carsties/assets/59537000/f6b121b1-4e9a-4a0f-a96d-db60ca905587)

