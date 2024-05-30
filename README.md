# VolleyDB-Application
a database management system designed for the Turkish Volleyball Federation.

## Introduction

VolleyDB Application is a database management system designed for the Turkish Volleyball Federation. It aims to systematically manage players' data and ensure reliability, consistency, and security in data management.

## Features

- Implemented database management system for players, coaches, juries, positions, teams, and match sessions.
- Developed user interface (UI) to support various operations like login, adding new users, updating stadium names, deleting match sessions, and more.
- Refinement of schema based on functional dependencies (FDs) and normalization.
- Captured additional constraints using CHECK construct and other means like triggers and procedures.

## How to Run

To run the VolleyDB Application locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the `VolleyDB-Application` directory in your terminal or command prompt.
3. Set up a virtual environment (optional but recommended):
    ```bash
    python3 -m venv env
    ```
4. Activate the virtual environment:

    - On Windows:
        ```bash
        .\env\Scripts\activate
        ```

    - On macOS and Linux:
        ```bash
        source env/bin/activate
        ```

5. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
6. Navigate to the `db_project` directory:
    ```bash
    cd db_project
    ```
7. Apply database migrations:
    ```bash
    python manage.py migrate
    ```
8. Start the development server:
    ```bash
    python manage.py runserver
    ```
9. Open a web browser and access the application at `http://127.0.0.1:8000/`.
