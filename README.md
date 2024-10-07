# E-commerce Website (Django) - Installation Guide

This project is an e-commerce website built with Django. Follow the instructions below to install and run the project locally.
Project Demonstration:
https://drive.google.com/file/d/1AeF_o4FtQHZTdOqiub53rQJsJEqd1Bs9/view?usp=drive_link

## Prerequisites

Ensure you have the following installed on your machine before proceeding:

- **Python 3.8+**
- **pip** (Python package manager)
- **Virtualenv** (recommended)
- **Git** (for cloning the repository)


## Steps to Install

### 1. Clone the Repository

Use Git to clone the project repository to your local machine:

```bash
git clone https://github.com/yxsh7/Ecommerce-Project-Django.git
cd Ecommerce-Project-Django
```

### 2. Set Up a Virtual Environment

It’s recommended to create and activate a virtual environment for managing dependencies:

```bash
# Install virtualenv if you don't have it
pip install virtualenv

# Create a virtual environment
virtualenv venv

# Activate the virtual environment

# On Windows
venv\Scripts\activate

# On macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies

With the virtual environment activated, install all required dependencies:

```bash
pip install -r requirements.txt
```


### 4. Apply Migrations

Run the following command to apply database migrations:

```bash
python manage.py migrate
```

### 5. Create a Superuser (Admin)

To create an admin user for accessing the Django admin dashboard, run:

```bash
python manage.py createsuperuser
```

### 6. Run the Development Server

Start the Django development server:

```bash
python manage.py runserver
```

You can now access the website by navigating to `http://127.0.0.1:8000/` in your browser.
