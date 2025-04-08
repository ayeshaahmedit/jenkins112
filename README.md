# DevOps Task 2 - Jenkins CI/CD Pipeline

## Objective
Create a Jenkins pipeline to automate building and deploying a simple app using Docker.

## Tech Stack
- Jenkins
- Docker
- Python (Flask)

## Jenkinsfile Stages
- **Clone**: Clones the GitHub repo.
- **Build**: Builds a Docker image.
- **Test**: Dummy test step (can be extended).
- **Deploy**: Runs the app in a Docker container.

## How to Run
1. Clone repo
2. Run `docker build -t my-app .`
3. Run `docker run -d -p 5000:5000 my-app`
4. Visit `http://localhost:5000` to test

## Author
Your Name
