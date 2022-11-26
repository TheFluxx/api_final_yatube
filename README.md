Как установить?

Создаем виртуальное окружение:

$ python -m venv venv

Устанавливаем зависимости:

$ pip install -r requirements.txt

Создаем миграции:

$ python manage.py makemigrations 
$ python manage.py migrate

Запускаем сервер:

$ python manage.py runserver
