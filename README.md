# Jenkins CI/CD Pipeline with Docker and Flask

## Project Overview

Built and successfully executed a Jenkins CI/CD pipeline on AWS EC2 that automated Docker image builds and pushed a Flask application to Docker Hub. Verified successful pipeline execution and confirmed the published container image.

This hands-on project demonstrates my experience with continuous integration, containerization, cloud infrastructure, and deployment automation.

## Technologies Used

- **AWS EC2** — Hosted the Jenkins automation environment.
- **Jenkins** — Automated the CI/CD pipeline.
- **Docker** — Built and packaged the Flask application into a container image.
- **Python and Flask** — Developed the web application.
- **GitHub** — Managed application source code and project documentation.
- **Docker Hub** — Stored the successfully published container image.

## CI/CD Workflow

1. Jenkins retrieves application source code from GitHub.
2. Jenkins builds a Docker image using the Dockerfile.
3. Jenkins authenticates with Docker Hub using stored credentials.
4. Jenkins pushes the newly built image to Docker Hub.
5. The completed pipeline reports a successful build.

## Verified Project Results

- Successfully executed the original Jenkins pipeline with the result **Finished: SUCCESS**.
- Built and pushed the Flask application image to Docker Hub.
- Verified the published Docker image with tag `2`.
- Recovered the original Flask application source from the published image.
- Successfully rebuilt and tested the Flask application locally using Docker.
- Confirmed the application displayed: **Hello from my Jenkins Docker application!**

## Published Docker Image

**Docker Hub Repository:** https://hub.docker.com/r/5dwayne/jenkins-flask-app

**Verified Image Tag:** `2`

## Project Files

- `app.py` — Original Flask application recovered from the published Docker image.
- `requirements.txt` — Python application dependency.
- `Dockerfile` — Docker build configuration recreated and successfully tested locally.
- `Jenkinsfile` — Reconstructed pipeline configuration based on the completed Jenkins workflow.
- `.gitignore` — Excludes temporary and sensitive files from Git tracking.
- `.dockerignore` — Excludes unnecessary files from Docker builds.

## Skills Demonstrated

- CI/CD pipeline automation
- Jenkins pipeline configuration
- Docker image creation and container management
- AWS EC2 infrastructure administration
- Git and GitHub version control
- Docker Hub image publishing
- Application troubleshooting and validation

## Project Outcome

This project strengthened my hands-on understanding of how Jenkins, Docker, GitHub, and AWS work together to automate application delivery. I successfully completed the original CI/CD workflow and verified that the published Flask application could be recovered, rebuilt, and run in Docker.