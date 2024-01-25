# Flask, Tailwind и Flowbite

Заготовка для создания сайта с помощью backend-фреймворка [Flask](https://flask.palletsprojects.com/) (Python), frontend-фреймворка [Tailwind](https://tailwindcss.com/) и библиотекой готовых компонентов [Flowbite](https://flowbite.com/)

> [!NOTE]
> Для успешного запуска потребуется установленный [Python](https://www.python.org/downloads/) и [NodeJS](https://nodejs.org/en/download/current).

## Для установки проекта
1. Клонируем репозиторий и заходим в папку
```sh
git clone https://github.com/makehtml/ftf-boilerplate.git && cd ftf-boilerplate
```
2. Устанавливаем виртуальное окружение питона
```sh
python3 -m venv venv
```
3. Активируем виртуальное окружение питона
```sh
source venv/bin/activate
```
(mac/linux)
```sh
venv/Scripts/activate.bat
```
(win/cmd)

4. Устанавливаем зависимости Python
```sh
pip install -r requirements.txt
```
5. Устанавливаем зависимости для NodeJS
```sh
npm i
```

## Для запуска проекта и разработки
1. Заходим в папку проекта и активируем виртуальное окружение питона
```sh
source venv/bin/activate
```
(mac/linux)
```sh
venv/Scripts/activate.bat
```
(win/cmd)

2. Запускаем Flask
```sh
flask run --debug
```
3. Открываем вторую консоль и заходим в папку проекта
4. Запускаем компилятор стилей
```sh
npx tailwindcss -i ./src/css/styles.css -o ./static/css/styles.css --watch
```
5. Редактируем шаблоны в папке `/templates`, при использовании новых классов в разметке — будет генерироваться новый файл стилей
