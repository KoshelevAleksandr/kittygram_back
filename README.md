# Kittygram
Учебный проект для Яндекс.Практикум
### Описание
Социальная сетью для обмена фотографиями любимых питомцев.
### Технологии
- Python 3.7
- Django 2.2.19
- SQLite
- Simple-JWT

### Frontend для Kittygramm:
https://github.com/KoshelevAleksandr/kittygram_frontend
### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:KoshelevAleksandr/kittygram_back.git
```

```
cd kittygram_back
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
