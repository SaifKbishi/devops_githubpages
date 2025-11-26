# My GitHub Actions App 
## Overview
A simple Flask application containerized with Docker, demonstrating multiple routes and basic web functionalities.
Hosted in GitHub pages and managed by GitHub Actions.

## Features
- Flask server with multiple routes
- Dockerized for easy deployment
- non-Responsive HTML templates
- Environment configuration management
- Helm package
- Github Actions
_ Github Pages

## Technologies
- Python 3.10-slim
- Flask
- Docker
- HTML
- K8s
- Helm
- GiHub Actions
- GitHub pages

## Getting Started

### Prerequisites
- [Python](https://www.python.org/downloads/) installed
- [Docker](https://www.docker.com/get-started) installed
- [Docker Desktop](https://docs.docker.com/desktop/setup/install/windows-install/) installed

### Setup from Github 
Build and Run the Project:
- In your terminal, navigate to the project directory and run:
- Clone the repository
```bash
    git clone https://github.com/SaifKbishi/devops_githubpages.git
    cd devops_finalproject
```
```bash
    docker build -t 19820401/finalproject:1.0.1 .
```
```bash
    docker run -d -p 5008:5008 --name finalproject-cntnr0.1 -v finalproject_volume:/app/static 19820401/finalproject:1.0.1
```

    Then in your browser go to (http://127.0.0.1:5008/)

### Setup from Docker hub 
Build and Run the Project:
- In your terminal, navigate to the project directory and run:
- Pull the image from Docker Hub:
```bash
    docker pull 19820401/finalproject:1.0.1
```
```bash
    docker run -d -p 5008:5008 --name finalproject-cntnr0.1 -v finalproject_volume:/app/static 19820401/finalproject:1.0.1
```
    Then in your browser go to (http://127.0.0.1:5008/)