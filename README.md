# social-media-fastapi

A robust REST API built with FastAPI, featuring user authentication, PostgreSQL integration, and containerized deployment.

## Features

- User authentication with JWT tokens
- Password hashing for secure storage
- PostgreSQL database integration
- Docker containerization
- Automated testing with pytest
- CI/CD pipeline with GitHub Actions
- Production deployment on Ubuntu VM
- Custom domain configuration (atharva.my)
- SSL/TLS encryption with Let's Encrypt
- HTTPS-only secure access

## Tech Stack

- FastAPI
- PostgreSQL
- SQLAlchemy
- Alembic (for database migrations)
- pytest (for testing)
- Docker
- GitHub Actions
- Gunicorn (WSGI HTTP Server)
- Nginx (Reverse Proxy)
- Ubuntu Server (VM)
- Certbot (SSL/TLS certificates)
- Let's Encrypt (Certificate Authority)
- Custom Domain (atharva.my)

## Prerequisites

- Python 3.8+
- PostgreSQL
- Docker (optional)

## Production Deployment

### Server Requirements
- Ubuntu Server
- Python 3.8+
- PostgreSQL
- Nginx
- Gunicorn

## Local Development Setup

1. Clone the repository
2. Create and activate virtual environment
3. Install dependencies
4. Set up environment variables
5. Run database migrations
6. Start the application
   
## Docker Setup

1. Build the Docker image
2. Run the container


## API Documentation

Once the application is running, you can access:
- Swagger UI documentation at `/docs`
- ReDoc documentation at `/redoc`

## API Endpoints

### Authentication
- `POST /users/`: Create a new user
- `POST /login`: Login user and receive access token

### Protected Routes
- Requires JWT token authentication
- Include token in Authorization header: `Bearer <token>`

## Deployment

The application can be deployed using Docker and includes GitHub Actions workflows for automated testing and deployment.



   
