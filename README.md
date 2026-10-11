# Jenkins CI/CD Pipeline with Docker and AWS EC2

## Project Overview

Built and successfully executed a Jenkins CI/CD pipeline on an AWS EC2 instance to automate the building and publishing of a Dockerized Python Flask application.

This hands-on project demonstrates practical experience with continuous integration and continuous delivery (CI/CD), containerization, cloud infrastructure, and DevOps automation.

## Technologies Used

- Amazon Web Services (AWS EC2)
- Jenkins
- Docker and Docker Hub
- Git and GitHub
- Python Flask
- Linux (Amazon Linux 2023)
- Jenkins Pipeline (Jenkinsfile)

## Project Implementation

1. Launched an AWS EC2 instance running Amazon Linux 2023.
2. Installed and configured Docker on the EC2 instance.
3. Deployed Jenkins using a Docker container.
4. Configured Jenkins and installed the required plugins.
5. Created Docker Hub credentials within Jenkins for authenticated image publishing.
6. Configured a Jenkins pipeline using a Jenkinsfile.
7. Built a Docker image containing a Python Flask application.
8. Automated Docker Hub authentication and image publishing.
9. Successfully executed the Jenkins pipeline and verified the published Docker image in Docker Hub.

## CI/CD Workflow

GitHub Source Code → Jenkins Pipeline → Docker Image Build → Docker Hub Authentication → Docker Hub Image Push

## Project Results

- Successfully completed a Jenkins pipeline with a **SUCCESS** build status.
- Automated the Docker image build and publishing process.
- Verified that the Docker image and build tag were available in Docker Hub.
- Practiced troubleshooting Docker permissions, storage capacity, and pipeline configuration issues.

## Skills Demonstrated

- CI/CD pipeline development
- Jenkins automation
- Docker container management
- AWS EC2 administration
- Linux troubleshooting
- GitHub integration
- Container image publishing
- DevOps workflow fundamentals

## Future Improvements

- Add automated application tests to the pipeline.
- Integrate security scanning for Docker images.
- Configure GitHub webhooks to trigger builds automatically.
- Expand the pipeline to deploy applications to a staging environment.

## Project Status

**Completed:** Jenkins pipeline successfully built and pushed a Docker image to Docker Hub.

*This repository documents a hands-on learning project. Source code and pipeline configuration will be added separately.*
