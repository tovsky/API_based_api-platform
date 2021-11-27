***Настройка проекта в dev окружении***
1. Скопировать файл `.env`  в `.env.local`  и подставить нужные значения переменных.

2. Установить зависимости проекта `composer install`

3. Запустить контейре с БД ``docker-compose up -d``

4. Применить миграции ``php bin/console doctrine:migrations:migrate`` 

5. Запустить встроенный сервер  ``php bin/console server:run``
    инструкция API станет доступна по адресу: http://localhost:8000/api/

