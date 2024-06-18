# LinkShortener

## Про проект

Цей проект розроблено в рамках домашних завдань «Технологія розробки веб-додатків». Це веб-програма, яка скорочує URL-адреси та забезпечує зручний інтерфейс для керування ними.

## Автор

**Панченко Денис**

- **Група:** КВ-32мп

## Лабораторні роботи


### Технології розробки WEB - додатків


1. [Lab Work 1](https://docs.google.com/document/d/1c0NWXGc5CbxMudneEEIbsn-IYrygieXd1nbatY0FPIQ/edit?usp=sharing)
2. [Lab Work 2](https://docs.google.com/document/d/1X8an6SW-esjYKtjIWe4fxX4kF21VUQINNtaPQIxxfuE/edit?usp=sharing)
3. [Lab Work 3](https://docs.google.com/document/d/1g-e5p-b5K7SJwb6DbBUk2w-FTxsW8IVSHL4yPrzotf0/edit?usp=sharing)


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

