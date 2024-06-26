# Django-React CRUD Application

This project demonstrates a CRUD (Create, Read, Update, Delete) application using Django and React. It includes setting up the backend with Django, creating APIs, and integrating the frontend with React.

## Features

- **Django Backend**: Handles data and provides REST APIs.
- **React Frontend**: User-friendly interface for interaction.
- **CRUD Operations**: Create, read, update, and delete records.

## Prerequisites

- Python 3
- Django
- Node.js
- npm or yarn

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/django-react-crud.git
   cd django-react-crud


## Backend Setup:

1. **Create a virtual environment:**
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

## Install dependencies:
```bash
pip install -r requirements.txt
```

## Run migrations:
```bash
python manage.py migrate
```

## Start the Django server:
```bash
python manage.py runserver
```

## Frontend Setup:

1. **Navigate to the frontend directory:**
```bash
cd frontend
```

## Install dependencies:
```bash
npm install  # or yarn install
```

## Start the React development server:
```bash
npm start  # or yarn start
```

## Usage:

Navigate to http://localhost:3000 in your browser to view the application.

Use the interface to perform CRUD operations.

## Project Structure
- backend_project/: Contains the Django project and apps.
- backend_api/: Contains the Django project and apps.
- frontend/: Contains the React application.

## License
This project is licensed under the MIT License.
