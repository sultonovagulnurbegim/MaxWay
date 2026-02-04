MaxWay


- Python 3.8+
- Django 4.0+


```bash

git clone https://github.com/foydalanuvchi/repository-nomi.git


python -m venv venv


# Windows: venv\Scripts\activate
# Linux/Mac: source venv/bin/activate


pip install -r requirements.txt


python manage.py migrate


python manage.py createsuperuser


python manage.py runserver