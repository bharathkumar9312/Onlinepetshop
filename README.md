# Django Setup Steps

Here's a breakdown of the steps taken to set up a Django project:

1.  **Install Django:**
    ```bash
    pip install django
    ```

2.  **Check Python Version:**
    ```bash
    python --version
    ```

3.  **Install `pipenv` (for virtual environments):**
    ```bash
    pip install pipenv
    ```

4.  **Activate the Virtual Environment:**
    ```bash
    pipenv shell
    ```

5.  **Install Django (within the virtual environment):**
    ```bash
    pip install django
    ```

6.  **Use `django-admin` (Django command-line tool):**
    ```bash
    pip django-admin
    ```

7.  **Create a New Django Project (e.g., "petshop"):**
    ```bash
    django-admin startproject petshop
    ```

8.  **Run the Development Server:**
    ```bash
    python manage.py runserver
    ```

9.  **Install `psycopg2-binary` (for PostgreSQL):**
    ```bash
    pip install psycopg2-binary
    ```

10. **Create a Django App (e.g., "petapp"):**
    ```bash
    python manage.py startapp petapp
    ```

11. **Install Pillow (for image processing):**
    ```bash
    pip install pillow
    ```

12. **Make Migrations:**
    ```bash
    python manage.py makemigrations
    ```

13. **Apply Migrations:**
    ```bash
    python manage.py migrate
    ```

14. **Create a Superuser:**
    ```bash
    python manage.py createsuperuser
    ```

15. **Access the Admin Panel:**
    Open your browser and navigate to `/admin`.

16. **Install `django-jazzmin` (for a better admin interface):**
    ```bash
    pip install django-jazzmin
    ```
