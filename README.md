# Cupcake API

## Setup

1. Create a virtual environment and install dependencies:
    ```bash
    python -m venv venv
    source venv/bin/activate  # or venv\Scripts\activate for Windows
    pip install -r requirements.txt
    ```

2. Create the database and seed it:
    ```bash
    python seed.py
    ```

3. Run the application:
    ```bash
    python app.py
    ```

4. Run tests:
    ```bash
    python -m unittest -v tests
    ```

## Endpoints

- **GET /api/cupcakes**: List all cupcakes.
- **GET /api/cupcakes/<id>**: Get a specific cupcake.
- **POST /api/cupcakes**: Create a new cupcake.
- **PATCH /api/cupcakes/<id>**: Update a cupcake.
- **DELETE /api/cupcakes/<id>**: Delete a cupcake.
