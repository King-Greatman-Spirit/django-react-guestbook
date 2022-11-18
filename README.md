# Installation guide

git clone https://github.com/King-Greatman-Spirit/django-react-guestbook.git

#Setup Backend
1. cd King-Greatman-Spirit/guestbook_api
2. python3.10 -m venv venv # Create a virtual environment
3. source venv/bin/activate # Activate venv on macOS.
4. source venv/Script/activate # Activate venv on windows.
5. pip install -r requirements.txt # Install libraries
6. python manage.py createsuperuser # create admin user
7. python manage.py runserver # run django server

#Setup Frontend

1. cd API-Authentication/King-Greatman-Spirit
2. npm install
3. npm start
