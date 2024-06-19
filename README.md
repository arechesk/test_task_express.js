# Тестовое задание Express.js

### Предварительные требования

Убедитесь, что на вашем компьютере установлен node.js.

### Запуск приложения

1. Склонируйте репозиторий: `git clone https://github.com/arechesk/test_task_express.js.git`
2. Перейдите в директорию проекта: `cd test_task_express.js`
3. Установите зависимости: `npm install`
4. Запустите приложение: `node app.js`

### Доступные маршруты

- / - главная страница
- /about - страница about

### Запуск с помощью docker

1. Соберите образ `docker build -t test_task .`
2. Запустите контейнер `docker run --rm -p 3000:3000 test_task`

