🚀 Strapi Docker Setup

A simple Docker configuration to build and run a Strapi v4 application using Node.js 20.

1st :- git clone 



🐳 Build the Image
docker build -t strapi-app .

▶️ Run the Container
docker run -p 1337:1337 strapi-app

🌐 Access the Application

Admin Panel: http://localhost:1337/admin

API Base URL: http://localhost:1337/api

📌 Notes

Runs Strapi in production mode

Uses SQLite as the default database

Designed for quick local setup and testing
