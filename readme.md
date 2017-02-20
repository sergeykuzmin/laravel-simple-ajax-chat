**Развертывание проекта**

**Необходимые компоненты:**

-PHP 7.*

-Mysql

**Этапы:**

1. Клонируем проект
2. В директории проекта запустить следующие команды: composer install и npm install

3. Добавить права доступа к /storage и к /bootstrap

4. Добавить вкорне проекта .env файл конфигурации ипо примеру .env.example добавить параметры
5. Запустить команду: php artisan key:generate
6. Запустить команду с миграциями: php artisan migrate
7. Запустить встроенный сервер php php artisan serve