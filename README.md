# WebLinkShrinker

## Project Overview

Цей проект розроблено в рамках домашних завдань «Технологія розробки веб-додатків». Це веб-програма, яка скорочує URL-адреси та забезпечує зручний інтерфейс для керування ними.

## Author

**Panchenko Denis**

- **Group:** KV-32mp
- **Faculty:** FAM

## Lab Works


### Web Application Development Technology


1. [Lab Work 1](https://docs.google.com/document/d/1eBmpXmZe8qkjatcnfJfWKnnoumhF4L6_BsW8mSHQ_kE/edit?usp=sharing)
2. [Lab Work 2](https://docs.google.com/document/d/1eWWa-pN45NHQ3wyEM7PdBn_ysjDAWXY4FZTiLwZJgIg/edit?usp=sharing)
3. [Lab Work 3](https://docs.google.com/document/d/1EqUQ4oR_zdguyaCTRyI_GR3XJ5a7H3pZUjnP9D-Q7qc/edit?usp=sharing)


### Початок роботи
## Необхідні умови
- Python 3.x
- Django
- Інші залежності, зазначені в requirements.txt

### Міграція бази даних
Запустіть наступну команду для застосування міграцій бази даних:

```bash
python manage.py migrate
```

### Cтворення суперкористувача
Щоб створити адміністратора, виконайте команду:

```bash
python manage.py createsuperuser
```

Слідуйте підказкам для створення облікового запису суперкористувача.

### Запуск сервера
Запустіть сервер розробки за допомогою команди:
```bash
python manage.py runserver
```
Відвідайте http://127.0.0.1:8000/, щоб отримати доступ до застосунку.


## Використання
### API Ендпоінти

- `/api/urls/` - Управління записами URL
- `/api/auth/` - Ендпоінти для автентифікації

### Панель адміністратора

Отримайте доступ до панелі адміністратора Django за адресою `http://127.0.0.1:8000/admin/` за допомогою облікових даних суперкористувача.

