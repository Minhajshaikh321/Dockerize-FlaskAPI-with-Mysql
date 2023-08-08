# Dockerize-Flask-API-with-Mysql
This repository provides a complete setup for quickly deploying a Flask-based API and a MySQL database within Docker containers. The Flask API includes customizable endpoints, while the MySQL database handles data storage.

 Make sure you have a requirements.txt file containing all the necessary Python packages, including Flask, SQLAlchemy, and mysqlclient for MySQL database connectivity.

 # To Run your application
 
 docker-compose build  # Build the Docker images
 
 docker-compose up     # Start the Docker containers

 docker logs -f [container id] # use to check logs

 
*Remember* to customize the database credentials and other configuration options to match your project requirements. Additionally, you might need to adjust the configurations for security and production environments.
