# Django React Project

This project is a simple web application that uses Django as the backend with a PostgreSQL database and React as the frontend. The API is documented using OpenAPI (Swagger). We are learning Kubernetes.

## Prerequisites

- Python 3.x
- Node.js (with npm)
- PostgreSQL

## Setup Instructions

1. **Clone the repository, set up the virtual environment, install dependencies, and configure the database:**

   ```code
   # Clone the repository
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

   # Set up the Python virtual environment
   ```code
   python -m venv env
   ```

   # On Windows use `env\Scripts\activate`
   ```code
   source env/bin/activate  
   ```

   # Install the required Python packages
   ```code
   pip install -r r.txt
   ```

   # Set up PostgreSQL database
   ```code
	python manage.py makemigrations
	```
	```code
	python manage.py migrate
	```
	
	```code
	python manage.py createsuperuser
	```

	```code
	python manage.py runserver
	```
