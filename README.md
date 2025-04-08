# DevOps Task 2 - Jenkins CI/CD Pipeline
📖 Project Explanation (Simple Words)
This project is about setting up a Jenkins CI/CD pipeline to automatically build and deploy a small web application using Docker.

Here’s what happens step-by-step:

You push code to GitHub — this triggers Jenkins.

Jenkins clones the code from your repo.

It builds a Docker image of the app (packages everything).

It runs a simple test to make sure things are working.

Then it deploys the app using Docker, so it's live and running.

All of this is done automatically using a file called a Jenkinsfile, which contains instructions for Jenkins on what to do in each step.

The goal is to learn how DevOps tools like Jenkins and Docker work together to make deployment fast and easy without manual work.

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
