# User Authentication Application - Django

## Overview
This Django application provides user authentication functionality, including login, signup, forgot password, change password, a user dashboard, and a profile page. Access to certain pages is restricted based on authentication status.

## Features
1. **User Authentication**: Login with email or username and password.
2. **Login Page**: Fields for Username/Email and Password, with links for Sign Up and Forgot Password.
3. **Sign Up Page**: Fields for Username, Email, Password, and Confirm Password, with a link to the Login page.
4. **Forgot Password Page**: Field for Email to send reset instructions.
5. **Change Password Page**: Requires authentication. Fields for Old Password, New Password, and Confirm Password.
6. **Dashboard**: Accessible only to authenticated users. Displays a greeting message and links to the Profile and Change Password pages, with an option to logout.
7. **Profile Page**: Displays user information (Username, Email, Date Joined, Last Updated/Accessed) with options to go back to the Dashboard and logout.

## Project Structure
```
assignment/
    assignment/
        db.sqlite3
        manage.py
        assignment/
            __init__.py
            asgi.py
            settings.py
            urls.py
            wsgi.py
        userAuth/
            __init__.py
            admin.py
            apps.py
            forms.py
            models.py
            tests.py
            urls.py
            views.py
            migrations/
            templates/
                change_password.html
                dashboard.html
                forgot_password.html
                index.html
                login.html
                profile.html
                reset_complete.html
                reset_confirm.html
                reset_form.html
                reset_sent.html
                signup.html
```

## Setup Instructions

1. **Install Django**
   ```
   pip install Django
   ```
2. **Clone the Repository**
   ```
   git clone <repository-link>
   cd assignment
   ```
3. **Apply migrations**
   ```
   python manage.py migrate
   ```
4. **Create Superuser**
   ```
   python manage.py createsuperuser
   ```
5. **Run server**
   ```
   python manage.py runserver
   ```
6. Open web browser and type in localhost and hit enter.

## Demonstration Video
A demonstration video can be found [here](https://drive.google.com/file/d/1biy0UcA5ElclbP5-eiXYhxc0AlTeqn1o/view?usp=drive_link).

# Thanks for visiting!
