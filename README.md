## Наш второй сайт - интернет магазин

### Инструкции по установке:
### скачиваем этот проект через команду 
#### git clone https://github.com/edzen12/AutoDetailShop.git
### или скачиваем zip файл и раскаповываем
### после открываем в VSCode эту папку и после открываем терминал

### и пишем, если Windows
#### python -m venv venv
#### .\venv\Scripts\activate
#### pip install -r requirements.txt
#### python manage.py migrate
#### python manage.py createsuperuser
#### python manage.py runserver

### и пишем команды если MacOS/Linux
#### python3 -m venv venv
#### source venv/bin/activate
#### pip install -r requirements.txt
#### python manage.py migrate
#### python manage.py createsuperuser
#### python manage.py runserver