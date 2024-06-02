# Fibonacci Calculator CI/CD Project

This project is designed to help understand and execute a CI/CD workflow using a Fibonacci calculator application. The project consists of four main components: client, server, worker, and nginx. The CI/CD workflow integrates various tools and services including GitHub, GitHub Actions, AWS Elastic Beanstalk, ElastiCache (Redis), and Amazon RDS for PostgreSQL.

## Project Structure

- **client**: Contains the frontend of the application built with React.
- **server**: Contains the backend API built with Node.js and Express.
- **worker**: Contains the worker process that calculates Fibonacci numbers.
- **nginx**: Contains the configuration for Nginx used to serve the client and proxy requests to the server.

## CI/CD Workflow Components

- **GitHub**: For source code management and version control.
- **GitHub Actions**: For continuous integration and deployment automation.
- **AWS Elastic Beanstalk**: For deploying and managing the application environment.
- **AWS ElastiCache (Redis)**: For caching Fibonacci calculations.
- **Amazon RDS (PostgreSQL)**: For storing persistent data.
