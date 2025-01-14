# Trail Service API

This is a RESTful API for managing trails, features, and trail logs. It includes JWT-based authentication for secure access to the endpoints. The service allows users to view trails, add new trails, update existing trails, delete trails, and manage location points on trails.

## Key Features

- **JWT Authentication**: Secure API access with JWT tokens.
- **CRUD Operations**: Create, Read, Update, and Delete trails and location points.
- **Role-based Access Control**: Only authorized users (Admin or User) can access certain routes.
- **Swagger UI**: Interactive API documentation for easy testing and exploration.

## Prerequisites

Before deploying the application, make sure you have the following installed:

- **Docker**: To run the app inside a container.
- **Python 3.11+**: To develop or run the application locally.
- **Docker Compose** (optional but recommended): To manage multiple services if needed.
- **pip** (Python package manager): To install required Python dependencies.
