# Introduction: ecommerce-django

- A project to demonstrate an end-to-end working of e-commerce project
- Utilizes django framework for rapid application development (RAD)

# Setup
## Setup virtualenv & install requirements
```
virtualenv venv -p python3
source venv/bin/activate
pip install -r requirements.txt
```

## Prepare for first run
```
python manage.py migrate
python manage.py createsuperuser
```

## Run
```
python manage.py runserver
```

## Visit site
- http://localhost
- http://localhost/admin

# Thank you!