
DevOps Microservices Project

Project Overview

This project contains three independent microservices:

1. User Service
2. Product Service
3. Order Service

The application uses Docker to containerize each service and Docker Compose to run all services together. Nginx acts as a reverse proxy.

Technologies Used

- Python Flask
- Docker
- Docker Compose
- Nginx
- Git and GitHub

Project Structure

devops-microservices/
├── user-service/
├── product-service/
├── order-service/
├── nginx/
│   └── nginx.conf
└── docker-compose.yml

Application Endpoints

- User Service: http://localhost:8080/users
- Product Service: http://localhost:8080/products
- Order Service: http://localhost:8080/orders

How to Run the Project

1. Clone the repository.
2. Open the project directory.
3. Start the containers:

docker compose up -d --build

4. Check running containers:

docker compose ps

5. Open the application endpoints in a browser.

Stop the Application

docker compose down

Project Flow

GitHub → Docker → Docker Compose → Nginx → Microservices
