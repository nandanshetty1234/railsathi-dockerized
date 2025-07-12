 RailSathi Dockerized 🚂
 Setup Instructions

 Clone the repo:
   ```bash
   git clone https://github.com/nandanshetty1234/railsathi-dockerized.git
   cd railsathi-dockerized
Add your .env file using .env.example as a guide.

Run the app with Docker:

bash
Copy
Edit
docker compose up --build
Visit:

http://localhost:8000/ ➝ Welcome message

http://localhost:8000/items/ ➝ JSON API

Tech Stack
Python 3.10

Django 5.2

PostgreSQL 14

Docker + Docker Compose
 
 
 Features
Dockerized Django app

PostgreSQL container

Configured using .env

Simple JSON endpoint (/items/)

Custom welcome homepage (/)
