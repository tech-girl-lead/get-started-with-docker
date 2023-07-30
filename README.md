## This project is a simple introduction to Docker. 

It includes a Dockerfile that builds a simple Node.js application, as well as a few scripts that can be used to run the application locally and in a Docker container

# Getting Started
To get started, make sure you have Docker installed on your system. Once Docker is set up, follow these steps:

1. Clone the project repository:

git clone  https://github.com/tech-girl-lead/get-started-with-docker.git
cd get-started-with-docker

2. Build the Docker image:

docker build -t node-app:1.0 .

3. Run the Application Locally

After building the Docker image, run the application on your local machine with the following command:

docker run -d -p 3000:3000 node-app:1.0

The application will be accessible in your browser at http://localhost:3000

If you have any improvements or fixes, please feel free to submit a pull request.
