## Starting the Project

To get started with the project, follow the steps below:

### 1. Environment Setup

1. Create a `.env` file at the root of the project based on the provided `.env_example` file.


    cp .env_example .env

2. Open the `.env` file and add the password and database name as necessary.

### 2. Docker Initialization

Run the following command to start the Docker containers:

    docker-compose up -d


This will start the necessary services for the project in the background.

### 3. Accessing the Application

After successful initialization, you can access the application in your browser at `http://localhost:PORT`, where `PORT` is the port configured in the `docker-compose.yml` file.

### 4. Stopping the Project

To stop the project and shut down the Docker containers, run:

    docker-compose down

This will terminate all services related to the project.
