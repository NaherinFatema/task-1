CI/CD Pipeline for Node.js Web App

This project demonstrates the process of automating code deployment using CI/CD with GitHub Actions, Node.js, and Docker. The pipeline is set up to build, test, and deploy the app every time changes are pushed to the main branch.

Project Overview

Objective: Set up a CI/CD pipeline to automate the testing, building, and deployment of a simple Node.js app.
Tools Used:
GitHub Actions for CI/CD automation
Docker for containerizing the Node.js app
Node.js for the web application
DockerHub for storing the Docker image How the Pipeline Works
Test: The pipeline will run tests on the code to ensure everything works as expected.
Build: The app will be built and containerized using Docker.
Push: The Docker image will be pushed to DockerHub for deployment.
This process will be automatically triggered whenever code is pushed to the main branch.

Folder Structure

Getting Started Locally

To run the Node.js app locally:

Clone this repository: bash git clone https://github.com/your-username/nodejs-demo-app.git cd nodejs-demo-app

Install dependencies: bash npm install

Start the app: bash node index.js

Open your browser and navigate to http://localhost:3000 to see the app running.

Docker Setup

This project uses Docker to containerize the Node.js app.

To build and run the Docker container locally:

Build the Docker image: bash docker build -t nodejs-demo-app .

Run the Docker container: bash docker run -p 3000:3000 nodejs-demo-app

Visit http://localhost:3000 in your browser.
