# API для социальной сети Yatube

## Описание

API для соцсети блогеров Yatube

#### Технологии

- Python 3.7
- Django 2.2.16
- Django Rest Framework 3.12.4
- Djoser 
- Simple JWT
- SQLite3

#### Запуск проекта

- Склонируйте репозиторий:  
``` git clone https://github.com:Anna751124/api_final_yatube.git ```    
- Установите и активируйте виртуальное окружение:  
``` python -m venv venv ```  
``` source venv/Scripts/activate ``` 
- Установите зависимости из файла requirements.txt:   
``` pip install -r requirements.txt ```
- Перейдите в папку api_yatube/yatube_api.
- Примените миграции:   
``` python manage.py migrate ```
- Выполните команду:   
``` python manage.py runserver ```

#### Примеры некоторых запросов API

Получить список всех постов:  
``` GET /api/v1/posts/ ```  
Добавление нового поста:  
``` POST /api/v1/posts/ ```   
Получить список всех групп:  
``` GET /api/v1/groups/ ``` 

#### Автор

Анна С.