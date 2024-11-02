#Django CRUD Web Application

## Description
This is a simple Django-based web application that provides full CRUD (Create, Read, Update, Delete) functionality. The project includes user authentication (registration, login, logout) and the ability to manage customer records.

## Features
- **User Authentication**: Register, login, and logout functionality using Django's built-in authentication system.
- **CRUD Operations**: Create, view, update, and delete customer records.
- **User Interface**: Clean and user-friendly interface using forms and messages for user feedback.

## Prerequisites
- Python (version 3.7+)
- Django (version 4.1+)
- MySQL (or an alternative database of your choice)

## Installation Instructions
1. **Clone the Repository**
2. **Navigate to the Project Directory**: `cd DjangoCrud`
3. **Create a Virtual Environment**: `python -m venv env`
4. **Activate the Virtual Environment**:
   - **Windows**: `env\Scripts\activate`
   - **MacOS/Linux**: `source env/bin/activate`
5. **Install Dependencies**
6. **Configure the Database**: Update `DATABASES` settings in `settings.py` with your MySQL credentials. Make sure MySQL server is running.
7. **Apply Migrations**: `python manage.py migrate`
8. **Create a Superuser**: `python manage.py createsuperuser`
9. **Run the Development Server**: `python manage.py runserver`
10. **Access the Application**: Open your browser and go to `http://127.0.0.1:8000/`

## Project Structure
- **views.py**: Contains the logic for handling requests and responses.
- **forms.py**: Contains form classes for user registration and adding records.
- **models.py**: Defines the data models for customer records.
- **templates/**: HTML templates for rendering the frontend.

## Usage
- **Home Page**: Lists all records and provides login functionality.
- **Register**: Users can sign up for an account.
- **Login/Logout**: Users can log in and out of their accounts.
- **Add Record**: Authenticated users can add a new record.
- **View Record**: Authenticated users can view details of a specific record.
- **Update Record**: Authenticated users can update an existing record.
- **Delete Record**: Authenticated users can delete a record.

## Technologies Used
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS (via Django templates)
- **Database**: MySQL
