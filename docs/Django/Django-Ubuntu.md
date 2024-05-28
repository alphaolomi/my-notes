# Get started with Django on Ubuntu

To get started with Django on Ubuntu, you can follow these steps. I'll provide you with the commands you need to run:

1. **Install Python and pip**:

   Ubuntu typically comes with Python pre-installed. To ensure you have Python and pip (Python package manager) installed, run the following commands:

   ```bash
   sudo apt update
   sudo apt install python3 python3-pip
   ```

2. **Create a Virtual Environment** (optional but recommended):

   It's a good practice to work within a virtual environment to isolate your Django project's dependencies. You can create one using the following commands:

   ```bash
   pip3 install virtualenv
   mkdir ~/django_projects  # Create a directory to store your Django projects
   cd ~/django_projects
   virtualenv .venv
   source .venv/bin/activate
   ```

3. **Install Django**:

   With your virtual environment activated (if you created one), you can now install Django:

   ```bash
   pip install django
   ```

4. **Create a Django Project**:

   You can create a new Django project using the following command. Replace `myproject` with your project's name:

   ```bash
   django-admin startproject notes-app
   ```

5. **Run the Development Server**:

   Navigate to your project folder and run the development server:

   ```bash
   cd notes-app
   python manage.py runserver
   ```

   Your Django development server should now be running, and you can access your project in a web browser at `http://localhost:8000`.

You can now start building your Django application.