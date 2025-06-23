## DevOps Assignment – Dhowfeek Hasan 

Thanks for the Opportunity

This repository contains a microservices-based web application with:

-  A **Go** service (Service 1)
-  A **Python Flask** service (Service 2)
-  **Nginx** reverse proxy
-  Dockerized and orchestrated using **Docker Compose**

---

## Project Structure
![image](https://github.com/user-attachments/assets/3ce0e29b-a444-4bf4-aa65-ab62aeb734a0)


## 2. Run Docker Compose
    docker-compose up --build
This will:

- Build both microservices

- Build the Nginx image

- Set up internal networking

- Start the services

## 3. Access the Services 

| Service        | URL                                    |
| -------------- | -------------------------------------- |
| Go Service     | `http://localhost:8080/service1/hello` |
| Python Service | `http://localhost:8080/service2/hello` |

## 4. Stopping the Services
     - docker-compose down -v
This command removes containers, networks, and volumes.

  ## License
This project is submitted as part of a DevOps assignment by Dhowfeek Hasan. Use for educational/demo purposes only.




