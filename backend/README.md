# SmartPath Backend API

This is the backend API for the SmartPath application built with FastAPI and Docker.

## Requirements

- Python 3.8+
- Docker
- Docker Compose

## Setup and Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd backend
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r app/requirements.txt
```

## Running the Application

### Using Docker

1. Build and start the containers:
```bash
docker-compose up --build
```

### Without Docker

1. Make sure you're in the virtual environment
2. Run the FastAPI application:
```bash
uvicorn app.main:app --reload
```

The API will be available at http://localhost:8000

## API Documentation

Once the application is running, you can access:
- Interactive API documentation (Swagger UI): http://localhost:8000/docs
- Alternative API documentation (ReDoc): http://localhost:8000/redoc

## Development

- The application uses FastAPI framework
- Auto-reload is enabled for development
- CORS is configured to allow all origins (customize in production)

## Testing

To run tests:
```bash
pytest
``` 