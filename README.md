# Software Architecture and Development - The Bug Hunters
 
This repository contains the source code for a microservices-based application as part of the Software Architecture and Development course. Follow the instructions below to set up and run the application locally using Docker.
 
## Getting Started
 
### 1. Clone the Repository
 
git clone https://github.com/Study-Program-Applied-Computer-Science/software-architecture-and-development-thebughunters.git
 
 
### 2. Navigate to the Project Directory
 
cd software-architecture-and-development-thebughunters
 
 
### 3. Build and Run the Application Using Docker Compose
 
docker-compose up --build
 
 
### 4. Register an Account
- Visit the frontend application after the services have started.
- Register with a valid **email**, **username**, and **password**.
 
### 5. Email Confirmation and Login
- Check your registered email for a confirmation link.
- Confirm the email and log in to access the application.
 
---
 
## Swagger Documentation
 
The application consists of several microservices, each with its own API documentation accessible through Swagger:
 
- **User Service:** [http://localhost:5002/api-docs/](http://localhost:5002/api-docs/)
- **Product Service:** [http://localhost:5004/swagger-ui/index.html](http://localhost:5004/swagger-ui/index.html)
- **Order Service:** [http://localhost:5003/docs#/](http://localhost:5003/docs#/)
- **Payment Service:** [http://localhost:5005/swagger-ui/index.html](http://localhost:5005/swagger-ui/index.html)
 
---
 
## Docker Images
 
The following are the Docker images used by the application:
 
| Service         | Docker Image                                |
|-----------------|---------------------------------------------|
| **Frontend**     | `manojp27/thebughunters-frontend`          |
| **Auth Service** | `manujana/node-authservice:latest`         |
| **User Service** | `manujana/node-userservice:latest`         |
| **Product Service** | `pramukhprakash/product`               |
| **Order Service** | `1255555/orderservice`                   |
| **Payment Service** | `pramukhprakash/payment`               |
 
## Environment Setup

To run this project, you need to configure the environment variables using the provided `.env` files. Follow the instructions below to download and set them up.

### Step 1: Download the `.env` Files
The `.env` files required for the project can be found at the following Google Drive link:

[Download .env files from Google Drive](<https://docs.google.com/document/d/18X93x3kJM7F2iyxDjF9U7CRVwD2Hox9O/edit?usp=sharing&ouid=105734300263154750995&rtpof=true&sd=true>)

### Step 2: Place the Files in the Correct Location
Once downloaded, place the `.env` files in the root directory of the project (or the appropriate subdirectories if specified).
 




