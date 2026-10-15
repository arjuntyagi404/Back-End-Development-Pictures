# Back-End Development Pictures

## Project Overview

This project is a Python Flask microservice for working with picture data. It provides API endpoints for checking service health, retrieving picture records, and performing supported picture operations.

## Environment Setup

### Prerequisites

- Python 3.9.x
- Git
- A terminal or command-line environment

### Create the Project

Create or clone the `Back-End-Development-Pictures` repository from the course-provided project template.

### Run the Setup Script

From the project root directory, run:

```bash
bin/setup.sh
```

Review the script output and confirm that setup completes successfully.

### Activate the Virtual Environment

The expected virtual environment name is `backend-pics-venv`. If the setup script creates it, activate it using the command appropriate to your shell. For a typical Bash environment:

```bash
source backend-pics-venv/bin/activate
```

If the script uses a different environment location, follow the path reported by the script.

### Run the Application

Follow the project's configuration and instructions to start the Flask application. Confirm that the service starts successfully before testing its endpoints.

## Testing

Run the automated tests from the project root:

```bash
pytest
```

The test suite can be used to verify the health endpoint, picture retrieval, and supported picture operations.

## Notes

Use the course lab instructions for the expected environment, configuration, and API endpoints.
