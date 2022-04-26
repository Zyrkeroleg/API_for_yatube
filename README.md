<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Project logo"></a>
</p>

<h3 align="center">Yatube API</h3>

## 🧐 About <a name = "about"></a>

API для Yatube проекта. Поможет вам получить всю необходимую информацию о постах, комментариях и подписках.

## 🏁 Getting Started <a name = "getting_started"></a>

Эта инструкция поможет вам работать с данным API.

### Prerequisites

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Zyrkeroleg/api_final_yatube.git
cd api_final_yatube
```

### Installing

Cоздать и активировать виртуальное окружение:
```
python3 -m venv venv
source venv/bin/activate
```
Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
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
Для вашего удобства есть отличная документация, которая поможет вам разобраться во всё разнообразии возможностей данного API:
```
http://127.0.0.1:8000/redoc/
```

Спасибо, что выбрали наше API.🎉