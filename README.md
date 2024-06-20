# Django To-Do List

Этот проект представляет собой простое веб-приложение To-Do List, разработанное с использованием Django.

## Функциональность

- Создание новых задач.
- Отображение списка задач.
- Удаление задач.

## Установка и запуск

Для установки и запуска проекта выполните следующие шаги:

1. Клонировать репозиторий:
   ```bash
   git clone https://github.com/daniilyrkin/django_todo.git
   cd django_todo
   ```

2. Создать и активировать виртуальное окружение (опционально, но рекомендуется):
   ```bash
   python -m venv venv
   source venv/bin/activate  # На Windows: venv\Scripts\activate
   ```

3. Установить зависимости:
   ```bash
   pip install -r requirements.txt
   ```

4. Применить миграции базы данных:
   ```bash
   python manage.py migrate
   ```

5. Запустить сервер разработки Django:
   ```bash
   python manage.py runserver
   ```

6. Откройте браузер и перейдите по адресу `http://127.0.0.1:8000/` для доступа к приложению.

## Использование

- Для создания новой задачи перейдите на страницу `http://127.0.0.1:8000/task/create/`.
- Для удаления задачи используйте кнопку "Delete" рядом с каждой задачей на странице `http://127.0.0.1:8000/`.
