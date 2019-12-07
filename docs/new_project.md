Starting a New Django Project
=============================

# Folder setup

```bash
git clone peakmapper.com
cd peakmapper.com
python -m venv venv
source venv/bin/activate
pip install -U pip
pip install django
pip freeze > requirements.txt
python django-admin startproject peakmapper
cd peakmapper
python manage.py startapp ticklist
python manage.py runserver
```

