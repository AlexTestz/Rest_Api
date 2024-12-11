# Hello World REST API in Python - Docker Image

This Docker image contains a simple Python program using Flask that responds with "Hello, World!" when accessed via an HTTP GET request.

## Contents of the Image

The image includes the following files and configurations:

- **app.py**: The main Python script that defines the Flask application and sets up the /api/hello endpoint.
- **Dockerfile**: Configuration file that defines the Docker image, sets up the Python environment, and specifies the instructions to run the program when the container starts.
- **Python**: Uses the base Python image, version 3.9-slim.

## How to Use This Image

To run the program on your machine, make sure Docker is installed. Then, execute the following command in your terminal:


             docker run -d -p 5000:5000 alexmpz/hola-api


## Access the API
Once the container is running, you can access the API by navigating to:


            curl http://localhost:5000/api/hello


