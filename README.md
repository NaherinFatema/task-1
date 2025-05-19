Task 1: Automate Code Deployment Using CI/CD Pipeline (GitHub Actions)

• Objective:
Implement a CI/CD pipeline using GitHub Actions to build and deploy a Node.js app with Docker, automatically pushing the image to DockerHub.

• Technologies Used:
Node.js, Express.js, Docker, GitHub Actions, DockerHub

• Project Files:
• index.js – Node.js application code
• Dockerfile – Docker configuration for building the image
• .github/workflows/main.yml – GitHub Actions workflow for CI/CD
• package.json and package-lock.json – Project dependencies

• What the Workflow Does:
• Triggers on push to the main branch
• Logs in to DockerHub using GitHub secrets
• Builds a Docker image
• Pushes the image to DockerHub under the tag 'latest'

• GitHub Secrets Required:
• DOCKER\_USERNAME – Your DockerHub username
• DOCKER\_PASSWORD – Your DockerHub password or access token

• Image Repository:
The image is pushed to
docker.io/your-dockerhub-username/task-1\:latest
(Replace with your actual DockerHub username)

• Screenshots:
Screenshots of the GitHub Actions run and DockerHub image are included in the screenshots folder.

Naherin Fatema
