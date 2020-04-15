# todolist

Todo list for test [django-public-admin](https://django-public-admin.readthedocs.io/en/latest/).

## This project was done with:

* Python 3.7
* Django 2.2.12

## How to run project?

* Clone this repository.
* Create virtualenv with Python 3.
* Active the virtualenv.
* Install dependences.
* Run the migrations.

```
git clone https://github.com/rg3915/todolist.git
cd todolist
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
```