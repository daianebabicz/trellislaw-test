# Num to English API for Trellis Law ⚡

This Django application provides an API endpoint to convert numbers into their English word representations.

### Prerequisites

- Python (3.9.6
- Django (4.2.8)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/your-repo.git
    cd your-repo
    ```

2. Install dependencies and/or create a venv:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Django development server:

    ```bash
    python manage.py runserver
    ```

## API Endpoints

### 1. Convert Number to English (GET)

Use the following endpoint to convert a number to its English word representation using a `GET` request.

- **Endpoint**: `/api/num_to_english`
- **Method**: `GET`
- **Parameters**:
  - `number`: The numeric value to be converted (e.g., `/api/num_to_english?number=12345678`)

#### Example

    ```bash
    curl http://127.0.0.1:8000/api/num_to_english?number=12345678
    ```

### 2.Convert Number to English (POST)
Use the following endpoint to convert a number to its English word representation using a POST request.

- **Endpoint**: `/api/num_to_english`
- **Method**: `POST`
- **Body**: JSON object with a number key (e.g., {"number": "12345678"})

#### Example

    ```bash
    curl -X POST -H "Content-Type: application/json" -d '{"number": "123456}
    ```

