# FastAPI Application

This is a simple FastAPI application that provides a basic endpoint returning a "Hello, World!" message.

## Requirements

- Python 3.12 or higher
- [pip](https://pip.pypa.io/en/stable/installation/)

## Running Locally with Venv/Python in VS Code

### VS Code 

- Ensure that Python3 is installed on your local workstation
- Python3 extension for VS Code is installed
- Create a virtual environment by opening the command palette and running *Python: Create Environment*
- Select Venv from the dropdown
- Select the Version of Python3 that you're working with from the next dropdown
- Select the requirements.txt path
- Navigate to the /api directory in terminal
- Run ```uvicorn main:app --reload``` in terminal
- Navigate to http://localhost:8000 to see the startup response in your browswer

## Running Locally With Docker

1. Building the Docker image:
``` docker build -t cc-flipcard .```
1. Run the Docker container:
``` docker run -p 8000:8000 cc-flipcard ```
1. Open your browser to http://localhost:8000 to see the startup response in your browser

## API Endpoints

TODO