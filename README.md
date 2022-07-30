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
API начинается с /api/v1/
```
POSTS
Посты
```
api/v1/posts/ (GET, POST): Получить список всех постов или создать новый пост
api/v1/posts/{post_id}/ (GET, PUT, PATCH, DELETE): Получить, обновить, частично обновить или удалить пост по id
```
COMMENTS
Комментарии
```
api/v1/posts/{post_id}/comments/ (GET, POST): Получить список всех комментариев к посту или создать новый комментарий
api/v1/posts/{post_id}/comments/{comment_id}/ (GET, PUT, PATCH, DELETE): Получить, обновить, частично обновить или удалить комментарий к посту по id
```
AUTH
api/v1/token/ (POST): Получить JWT-токен
api/v1/token/refresh/ (POST): Обновить JWT-токен
```
FOLLOW
Подписки
```
api/v1/follow/ (GET, POST): Получить список всех подписчиков или создать подписку
```
GROUP
Группы
```
api/v1/group/ (GET, POST): Получить список всех групп или создать новую группу
```
Спасибо, что выбрали наше API.🎉
