
#### API Endpoints

 Endpoint | Functionality
--- | ---
`/api/user/create` | Create user
`/api/user/profile/{pk}` | Fetch user
`/api/user` | Fetch users
`/api-token-auth` | Fetch auth token
`/api/user/update/{pk}` | Change user
`/api/user/destroy/{pk}` | Delete user


## Installation 

Boot virtual env:

    pip install virtualenv
Clone this repo

    git clone https://github.com/p8ul/django-rest-framework-boilerplate
Create a virtual environment

    cd cd API-crud-drf
    virtualenv .venv
    source .venv/bin/activate
Install dependancy packages

    pip install -r requirements.txt
Make migrations & migrate

    python manage.py makemigrations
    python manage.py migrate
Create user
    
    python manage.py createsuperuser

## Launching the app
    python manage.py runserver

