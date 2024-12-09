# Product Management System

A robust backend system written in Go (Golang) for efficient product management. The application incorporates modern backend practices, including asynchronous workflows, caching mechanisms, and a scalable architecture.

---

## Features

### Core Functionalities
- **RESTful API**: Provides endpoints for creating, retrieving, and filtering products.
- **Asynchronous Image Processing**: Leverages RabbitMQ to handle image compression and storage workflows. (AWS S3 integration pending.)
- **Caching**: Implements Redis to optimize query performance and reduce database load.

### Developer-Friendly Tools
- **Structured Logging**: Uses Logrus for enhanced debugging and operational monitoring.
- **Robust Error Handling**: Includes retry mechanisms and dead-letter queues for reliability.

---

## Technologies Used
- **Programming Language**: Go (Golang)
- **Database**: PostgreSQL
- **Message Queue**: RabbitMQ
- **Caching**: Redis
- **Image Storage**: AWS S3 (setup pending)
- **Logging**: Logrus

---

## Setup Instructions

### Prerequisites
Ensure the following dependencies are installed and running:
- **Go**: Version 1.20 or higher
- **PostgreSQL**: Database for storing product information
- **Redis**: Caching system
- **RabbitMQ**: Message broker
