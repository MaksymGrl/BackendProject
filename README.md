# Backend Project
### Варіант лабороторної №3 = 16 mod 3 = 1 => валюти

This project was developed as part of the KPI server software development course. Right now it has a simple Flask application that provides a health check endpoint and REST API endpoint to work with in-memory stored data of users, categories and records.

## Prerequisites

- **Python:** Version 3.10 or later
- **pip:** Python package installer
- **virtualenv:** Optional, but recommended for isolating project dependencies.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MaksymGrl/BackendProject
   cd BackendProject
2. **Setting up Virtual Environment (Optional but recommended):**
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt

## Running the Application
  Start the Flask application using the following command:
  ```bash
  flask run --host=0.0.0.0 --port=5000
  ```
Once it's running, navigate to http://127.0.0.1:5000/healthcheck
