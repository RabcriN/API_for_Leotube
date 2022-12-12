## API for Leotube

### Описание:

API для социальной сети Leotube, написанный на DRF и документация к нему.

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке: 
```
git clone https://github.com/RabcriN/API_for_Leotube.git 
```

```
cd API_for_Leotube 
```


Cоздать и активировать виртуальное окружение:
Команда для установки виртуального окружения (Mac/Linux):
```
python3 -m venv env
source venv/bin/activate
```
Команда для Windows должна быть такая:
```
python -m venv venv
source venv/Scripts/activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

### Документация для API проекта находится по адресу:  
```
http://127.0.0.1:8000/redoc/ 
```
 
