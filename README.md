## BLOG app

## Description

A Django blog application that allows users to register, create new posts and update existing ones after logging in. Users can create accounts, log in and manage their blog posts.

## Features

- Registration of new users.
- Logging in and logging out.
- Creation of new blog entries.
- Updating existing entries by the author.
- Displaying a list of all entries.
- Ability to view details of each entry.

## Guide to Running a Django Application
1. **Prerequisites**

Make sure you have the following installed:

Python (recommended version is 3.8 or newer)
pip (Python package manager)
Django (installed via pip)

2. **Clone the repository**:
```bash
git clone <REPOSITORY_URL>
cd <FOLDER_NAME>
```

3. **Create a virtual environment (optional but recommended):**
```bash
python -m venv venv

source venv/bin/activate
# on Windows: venv\Scripts\activate
```

4. **Install the required libraries:**
```bash
pip install -r requirements.txt
```
5. **Setting Up the Database and Migrations:**
```bash
# Make sure you are in the directory containing manage.py
python manage.py migrate
```
6. **Creating a Superuser (Optional)**

To access the Django admin panel, you may want to create a superuser account:
```bash
python manage.py createsuperuser
```

7. **Running the Development Server**
```bash
python manage.py runserver
```

After starting the server, you should see a message like:

``` bash
Starting development server at http://127.0.0.1:8000/
```

