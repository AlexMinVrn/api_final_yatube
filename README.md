# api_final_yatube
Социальная сеть блогеров
### Описание
Социальная сеть, которая даст возможность пользователям создать учетную запись,
публиковать записи, подписываться на любимых авторов и отмечать понравившиеся записи.
### Технологии
Python 3.7
Django 2.2.19
django rest framework 3.12.4
### Запуск проекта в dev-режиме
- Установите и активируйте виртуальное окружение
- Установите зависимости из файла requirements.txt
```BASH
pip install -r requirements.txt
``` 
- Затем папке с файлом manage.py просто примените миграции: 
```BASH
python manage.py migrate
```
- В папке с файлом manage.py выполните команду:
```BASH
python manage.py runserver
```
### Автор
Александр Минаев