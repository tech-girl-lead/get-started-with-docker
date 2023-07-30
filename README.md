
# Get Started with Docker
This project serves as a simple introduction to Docker, providing a Dockerfile to build a basic Node.js application. It also includes a few scripts that facilitate running the application locally and within a Docker container.


## Prerequisites
To get started, make sure you have Docker installed on your system. Once Docker is set up, follow these steps:

## Clone the Project Repository

Use the following command to clone the project repository:

=> git clone  https://github.com/tech-girl-lead/get-started-with-docker.git
=> cd get-started-with-docker

## Build the Docker image:
Build the Docker image for the Node.js application using:

=> docker build -t node-app:1.0 .

## Run the Application Locally

After building the Docker image, run the application on your local machine with the following command:

=> docker run -d -p 3000:3000 node-app:1.0

The application will be accessible in your browser at http://localhost:3000

We welcome contributions to enhance and expand this "Get Started with Docker" project. If you have any improvements or fixes, please feel free to submit a pull request.
