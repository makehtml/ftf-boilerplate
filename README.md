# Заготовка для создания сайта с помощью backend-фреймворка [Flask](https://flask.palletsprojects.com/) (Python), frontend-фреймворка [Tailwind](https://tailwindcss.com/) и библиотекой готовых компонентов [Flowbite](https://flowbite.com/)

Для успешного запуска потребуется установленный [Python](https://www.python.org/downloads/) и [NodeJS](https://nodejs.org/en/download/current).

## Для установки проекта
1. Клонируем репозиторий `git clone https://github.com/makehtml/ftf-boilerplate.git`
2. Заходим в папку `cd ftf-boilerplate`
3. Устанавливаем виртуальное окружение питона `python3 -m venv venv`
4. Активируем виртуальное окружение питона `source venv/bin/activate` (mac/linux) `venv/Scripts/activate.bat` (win/cmd)
5. Устанавливаем зависимости для питона `pip install -r requirements.txt`
6. Устанавливаем зависимости для node `npm i`

## Для запуска проекта и разработки
1. Заходим в папку проекта и активируем виртуальное окружение питона `source venv/bin/activate` (mac/linux) `venv/Scripts/activate.bat` (win/cmd)
2. Запускаем Flask `flask run --debug`
3. Открываем вторую консоль и заходим в папку проекта
4. Запускаем компилятор стилей `npx tailwindcss -i ./src/css/styles.css -o ./static/css/styles.css --watch`
5. Редактируем шаблоны в папке /templates, при использовании новых классов в разметке — будет генерироваться новый файл стилей
