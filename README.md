# Softy Pinko Docker Project

## Description
This project is a simple web application using Docker.  
It includes a front-end, back-end, and a proxy server using Nginx.

The proxy handles all requests and routes them to the correct service.

---

## Services

- Front-end: Displays the website (Nginx)
- Back-end: Provides API data (Flask)
- Proxy: Routes requests between front-end and back-end

---

## How to Run

Build and start all services:

```bash
docker-compose up --build

Run with 2 back-end servers:
docker-compose up --build --scale back-end=2

Access

Open in browser:

http://localhost

API test:

http://localhost/api/hello

Features

Reverse proxy using Nginx
Load balancing (Round Robin)
Docker containerization
Microservices architecture
