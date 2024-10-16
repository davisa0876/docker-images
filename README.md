# Docker Compose Setup

This Docker Compose file is configured to run the following services:

- **MySQL**: A MySQL database server.
- **MinIO**: An S3-compatible object storage service.
- **MinIO Client (mc)**: A command-line tool for interacting with MinIO.

## Prerequisites

Before running this setup, make sure you have the following installed:

1. **Docker**: [Download and install Docker](https://docs.docker.com/get-docker/)
2. **Docker Compose**: [Install Docker Compose](https://docs.docker.com/compose/install/)

## How to Use

Follow the steps below to start the services:

### 1. Clone the Repository

If you haven't already, clone this repository:

```bash
git clone https://github.com/davisa0876/docker-images.git
cd docker-images
