# Docker Compose Demo App
This repository is a sample application for users following the getting started guide at https://docs.docker.com/get-started/.

The application is based on the application from the getting started tutorial at https://github.com/docker/getting-started

Welcome to the Docker Compose Demo App! This example application showcases how to use Docker Compose to manage multi-container applications.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Running the App with Docker Compose](#running-the-app-with-docker-compose)
- [Accessing the App](#accessing-the-app)
- [Stopping and Cleaning Up](#stopping-and-cleaning-up)
 
## Prerequisites

Before you begin, ensure you have the following prerequisites:

- Docker: Make sure you have Docker installed on your system. You can download and install it from the [official Docker website](https://www.docker.com/get-started).
- Docker Compose: Docker Compose should be available. You can typically find it pre-installed with Docker or install it separately if needed.

## Getting Started

To get started with this demo app, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/hrshkshri/docker-demo-app.git
   cd docker-demo-app

## Running the App with Docker Compose
    docker-compose up -d

## Accessing the App
    http://localhost:3000

## Stopping and Cleaning Up
    docker-compose down
## Customizing Configuration 
   You can customize the app's configuration by editing the docker-compose.yml file. Adjust service names, ports, volumes, and environment 
variables, and more according to your requirements.    
