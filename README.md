# Docker Todo App Project

## Project Overview

This project is a full-stack application that allows users to manage their tasks. Developed as part of a bootcamp, the project involves containerizing applications, creating connections between them, and orchestrating their operation. The primary focus is on enhancing Docker skills while simulating a real-world scenario.

## Development

### Technologies

- Docker
- Docker Compose
- Node.js
- Nginx
- React
- React Testing Library
- Jest
- React Router
- JavaScript
- HTML
- CSS

### Project Structure

The project is structured around multiple Docker containers, each serving a specific function:

- **01container:** This container is created in interactive mode using the Alpine image version 3.12.
- **02images:** This container runs the Nginx image version 1.21.3-alpine in the background, with its default access port mapped to port 3000 of the host system.
- **todobackend:** This image is built from the Dockerfile of the backend of the todo-app.
- **todofrontend:** This image is built from the Dockerfile of the frontend of the todo-app.
- **todotests:** This image is built from the Dockerfile of the tests of the todo-app.

### Project Requirements

The project successfully meets the specified requirements from the bootcamp readme:

- Container Creation: Creation of a container in interactive mode, without running it, naming it as 01container and using the Alpine image version 3.12.
- Container Initialization: Starting the 01container.
- Container Listing: Listing of containers filtered by the name 01container.
- Command Execution: Execution of the command cat /etc/os-release in the 01container without attaching to it.
- Container Removal: Removal of the 01container.
- Image Download: Download of the Nginx image version 1.21.3-alpine without creating or running a container.
- Container Running: Running a new container with the Nginx image version 1.21.3-alpine in the background, naming it as 02images and mapping its default access port to port 3000 of the host system.
- Container Stopping: Stopping the 02images container that is in progress.
- Dockerfile Creation: Creation of Dockerfiles for the backend, frontend, and tests of the todo-app.
- Docker-compose: Orchestration of applications using docker-compose so that backend, frontend, and tests can communicate.

## Feedback

Your feedback is invaluable! Please share your thoughts and suggestions regarding the project. I am eager to incorporate any insights you may have.

## Portfolio

Check out my [portfolio](my-folio-weld.vercel.app/) for more of my work!