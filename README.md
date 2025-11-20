Project Overview:

This project implements a secure user management system built with FastAPI, SQLAlchemy, and PostgreSQL. It includes a fully tested backend with unit tests, integration tests, and an automated CI/CD pipeline using GitHub Actions. The application is containerized with Docker and automatically built, scanned, and deployed to Docker Hub. The project demonstrates secure password hashing, data validation, and modern DevOps practices.

How to run tests locally:

python -m venv venv

source venv/bin/activate

pip install -r requirements.txt

pytest

How to run using Docker:

docker pull domsil12/assignment11:latest

docker run -p 8000:8000 domsil12/assignment11:latest

Docker Hub Repo:

https://hub.docker.com/r/domsil12/assignment11
