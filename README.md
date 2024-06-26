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


Backend Setup:

Create a virtual environment:
bash
Copy code
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Run migrations:
bash
Copy code
python manage.py migrate
Start the Django server:
bash
Copy code
python manage.py runserver
Frontend Setup:

Navigate to the frontend directory:
bash
Copy code
cd frontend
Install dependencies:
bash
Copy code
npm install  # or yarn install
Start the React development server:
bash
Copy code
npm start  # or yarn start
Usage
Navigate to http://localhost:3000 in your browser to view the application.
Use the interface to perform CRUD operations.
Project Structure
backend/: Contains the Django project and apps.
frontend/: Contains the React application.
Contributing
Contributions are welcome! Please open an issue or submit a pull request.

License
This project is licensed under the MIT License.
