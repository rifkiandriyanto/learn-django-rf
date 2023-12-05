# Learn Django RESTful API

This is a simple Django application showcasing RESTful API endpoints.

## Overview

This application serves as a playground to learn and experiment with Django REST Framework.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/rifkiandriyanto/learn-django-rf
    cd learn-django-rf
    ```

2. Create a virtual environment and activate it:

    ```bash
    python3 -m venv env
    source env/bin/activate
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the development server:

    ```bash
    python manage.py runserver
    ```

## Endpoints

### GET Endpoint

- Endpoint: `/`
- Method: GET
- Description: Retrieve data from the server.

### POST Endpoint

- Endpoint: `/add/`
- Method: POST
- Description: Add data to the server.

## Usage

Use tools like cURL, Postman, or any HTTP client to interact with the API endpoints.

### Example cURL Commands

#### GET Endpoint

```bash
curl http://127.0.0.1:8000/
```

#### POST Endpoint

```bash
curl -X POST -H "Content-Type: application/json" -d '{"name": "item #1"}' http://127.0.0.1:8000/add/
```

Replace `item #1` with the desired item name you want to add.