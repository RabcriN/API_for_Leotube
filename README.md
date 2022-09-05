Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

git clone https://github.com/RabcriN/api_final_yatube.git
cd api_final_yatube
Cоздать и активировать виртуальное окружение:

python -m venv venv
. venv/Scripts/Activate
Установить зависимости из файла requirements.txt:

python -m pip install --upgrade pip
pip install -r requirements.txt
Выполнить миграции:

python manage.py migrate
Запустить проект:

python manage.py runserver

Документация для API Yatube находится по адресу: 
http://127.0.0.1:8000/redoc/