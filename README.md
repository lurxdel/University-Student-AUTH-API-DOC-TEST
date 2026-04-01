# Student Management System - Authentication, API Documentation, and Testing

This project is a secured REST API for a Student Management System, built using the Django framework and Django REST Framework (DRF). It focuses on implementing industry-standard security patterns, interactive documentation, and robust testing.

### Features
- **Student API:** Full CRUD operations for managing student profiles and academic information.
- **JWT Authentication:** Secure API access using JSON Web Tokens (SimpleJWT), including token generation and refresh mechanisms.
- **API Documentation:** Interactive and auto-generated documentation using **Swagger/OpenAPI (drf-yasg)**.
- **Logging & Debugging:** Implementation of server-side logging to track API access and monitor system activities.

## Guide To Run
To run the system locally, do the following.
> - **Clone this repository** or download it as a **ZIP file.**
> - When cloning the repository, follow these steps.

### 1. Install Python
- Ensure you have Python installed. You can download it from [Python.org](https://www.python.org/).

### 2. Setting up the Backend
Navigate to the `student_api` directory and run the Django development server:

```bash
# Navigate to the project directory
cd student_api

# (Optional but recommended) Create and activate a virtual environment
python -m venv venv

# On Windows:
venv\Scripts\activate

# Install the required frameworks for this project
pip install django djangorestframework djangorestframework-simplejwt drf-yasg

# Run the database migrations (if needed)
python manage.py migrate

# Start the development server
python manage.py runserver
```

The backend will be running at `http://127.0.0.1:8000/`.

### 3. Available Endpoints and Documentation
- **Students API:** `http://127.0.0.1:8000/api/students/` (Requires Authorization)
- **Obtain Token:** `http://127.0.0.1:8000/api/token/` (POST username/password to get access token)
- **Token Refresh:** `http://127.0.0.1:8000/api/token/refresh/`
- **Swagger Documentation:** `http://127.0.0.1:8000/swagger/`


### Acknowledgment  
We are grateful to our instructors for their guidance and support throughout the development of this project. 

This work reflects my learning journey as a programmer.

## Disclaimer 
<div align="center"> 
  I do not own the images, names, information or references included in this project they are used purely as placeholders. <br> 
  All trademarks, service marks, trade names, and other intellectual property rights belong to their respective owners.  <br><br>

  Made with 💗 by <a href="https://github.com/lurxdel"><strong>Lurxdel</strong></a>
</div>
