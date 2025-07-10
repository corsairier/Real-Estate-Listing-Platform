# Real Estate Management Platform

## Overview
This project is a comprehensive web application for managing real estate properties. Built using the Django framework, it provides features for agents and buyers to interact seamlessly in a user-friendly environment.

## Features
### For Agents:
- Add, edit, and manage property listings.
- Upload property images and brochures.
- Access a dedicated dashboard for managing activities.

### For Buyers:
- View detailed property listings with images and descriptions.
- Rate and review properties.
- Find and interact with agents.
- Access a personalized dashboard for tracking activities.

### General Features:
- Secure user authentication (login/signup).
- Advanced search and filtering for property listings.
- Media file management for property images.
- Responsive and intuitive user interface.

## Technology Stack
- **Backend**: Django (Python)
- **Database**: SQLite
- **Frontend**: HTML, CSS, Django templates
- **Deployment**: WSGI/ASGI compatibility

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd real-estate-project
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Apply migrations:
   ```bash
   python manage.py migrate
   ```
5. Run the development server:
   ```bash
   python manage.py runserver
   ```

## Usage
- Open your browser and navigate to `http://127.0.0.1:8000/`.
- Create a superuser for admin access:
  ```bash
  python manage.py createsuperuser
  ```
- Log in and explore the platform.

## Folder Structure
- **`real_estate/`**: Main project folder containing settings and configurations.
- **`members/`**: Django app for user-related functionality (authentication, forms, views).
- **`media/`**: Uploaded property images.
- **`static/`**: Static assets like CSS and images.
- **`templates/`**: HTML templates for rendering the user interface.