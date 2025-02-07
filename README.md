# Flask Containerized App 🐳
A fully containerized Flask application using Docker. This project provides a lightweight and scalable setup for running Flask inside Docker containers, making deployment easy and efficient.

  🛠️ Prerequisites

   Ensure you have the following installed:

   Docker 🐳 (Install Docker)

   Docker Compose (Install Docker Compose)

📦 Setup & Run

1️⃣ Clone the Repository:-

      https://github.com/harshal-003/Flask-Containerized.git
      
      cd flask-containerized

2️⃣ Build and Run the Application:-

    docker compose up --build

3️⃣ Access the App:-

    http://localhost:5500

🔧 Stopping the Application

    docker-compose down

🏗️ How It Works

  Build Process: Docker uses the Dockerfile to build an image containing all necessary dependencies.

  Containerization: The application runs inside a container ensuring consistency across different environments.

   Orchestration: Docker Compose manages the Flask app and any additional services (e.g., database, caching) as defined in docker-compose.yml.

  Serving the Application: Flask runs on port 5500 inside the container, which is mapped to the host machine for access via http://localhost:5500.

   Stopping and Cleanup: Running docker-compose down stops the application and removes containers.

   


