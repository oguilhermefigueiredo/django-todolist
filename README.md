pip install django
export PATH="~/.local/bin/:$PATH"
python manage.py startapp tasks
python manage.py startapp hello
python manage.py startapp newyear
python manage.py migrate
python manage.py runserver
