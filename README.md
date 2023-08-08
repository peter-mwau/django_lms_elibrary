# django_lms_elibrary
It's a library management system that offers online management of books lending, returning, inventory and user management. It is developed using Django and bootstrap.

# How to Run
Download/Install the following
  1. Python (I used v3.9.1)
  2. PIP (for python modules installation)
Setup/Installation
1. Clone this repo
   ``git clone https://github.com/peter-mwau/django_lms_elibrary.git ``
2. Open your Terminal/Command Prompt window. (make sure to add "python" and "pip" in your environment variables)
3. Change the working directory to the extracted source code folder. i.e. cd C:/Users/Personal-23/Desktop/django_lms_elearning/django_lms
4. Activate the virtual environment using:
   ``source virtualenv/bin/activate``
5. Run the following commands:
  ```pip install -r requirements.txt
    python manage.py migrate
    python manage.py runserver
  ```
6. Keep the terminals open and running.
7. Open a web browser and browse http://localhost:8000/ or http://127.0.0.1:8000/
Note: I might forget to list some other modules/libraries. Kindly Install the missing modules if any occurred.

# Access Information for AdminSite
```SuperUser
Username: admin
Password: admin123
```

``http://127.0.0.1:8000/admin for the Django's Admin Site.``
