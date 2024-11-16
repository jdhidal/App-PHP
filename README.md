# Project in PHP 🌎

This is a basic program in PHP that displays a "Hello World" message on the web. The project uses Docker for containerization and has also been deployed on Heroku using the `test` branch.

## Prerequisites

Before you begin, make sure you have **PHP** installed on your system. You can download it from the official website:

[Download PHP](https://www.php.net)

## Project Cloning

To get started, clone this repository to your local machine using the following command:

```bash
git clone https://github.com/jdhidal/App-PHP.git
```

## Run Locally

To run the project locally on your machine:

1. **Navigate to the project directory**:
```bash
cd App-PHP
```

2. **Start the application**:
```bash
php -S localhost:8080
```
This will make the application available at http://localhost:8080.

## Build and Run with Docker

1. Build the Docker image: Make sure you are in the project directory and then run:
```bash
docker build -t app-php .
```

2. Run the container: Once the image is built, you can run the container:
```bash
docker run -p 8080:80 app-php
```
This will make the application available at http://localhost:8080.

## Docker Hub

The image for this project is also available on Docker Hub, allowing you to run it without needing to build it locally. You can get it by running:

```bash
docker pull jdhidalgo673/app-php:latest
```

```bash
docker run -p 8080:80 jdhidalgo673/app-php:latest
```

This will make the application available at http://localhost:8080.

## Deployment to Heroku

This project is deployed on Heroku, so you can access the application directly at the following link:

[Visit the Heroku website](https://app-php-d4fa4eabf2f1.herokuapp.com/)


Thanks for exploring this Hello World project in PHP! 😊