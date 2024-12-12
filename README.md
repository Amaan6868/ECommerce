# ECommerce Microservices Application

## Overview

ECommerce is a microservices-based application designed to manage projects, products, customers, and orders. This project integrates these functionalities into a cohesive search service that combines and utilizes data from all other services.

This application is built as a learning project, based on the [Azure Microservices with .NET Core for Developers](https://www.linkedin.com/learning/azure-microservices-with-dot-net-core-for-developers/making-sense-of-microservices-architecture-in-a-dot-net-core-and-azure-ecosystem?resume=false&u=106240434) tutorial from LinkedIn Learning.

## Features

- **Project Service**: Handles the creation and management of projects.
- **Product Service**: Manages products and their details.
- **Customer Service**: Manages customer data.
- **Order Service**: Handles order placement and management.
- **Search Service**: Combines data from all services for integrated search functionality.

## Microservices Architecture

The application employs a microservices architecture to ensure scalability, maintainability, and modularity. Each service operates independently, communicating via APIs.

### Key Components

- **Independent Services**: Each service is independently developed, deployed, and scaled.
- **Search Integration**: Combines and processes data from other services to provide a unified user experience.

## Technologies Used

- **.NET Core**: Backend framework for building services.
- **Azure**: Cloud platform for hosting and scaling services.
- **REST APIs**: Communication between microservices.
- **Database Integration**: Persistent storage for services.
