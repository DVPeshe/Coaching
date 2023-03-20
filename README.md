# Coaching
репозиторий для тренировки команды

# интернет-магазин
Приложение - продуктовый маркет.
При запуске приложения появляется главная страница магазина с приветствием.
На главной странцие есть несколько разделов - можно просматривать, откладывать в корзину и заказывать продукты, а также
просматривать свои заказы. Чтобы сделать заказ, нужно авторизоваться.
В режиме админа появляется новый раздел "Администрирование", в котором можно управлять продуктами и учетными записями
пользователей.

Пользователи по умолчанию для тестирования приложения:
1) логин: bob, пароль: 100 (обычный пользователь),
2) логин: john, пароль: 100 (пользователь - админ).

Запуск приложения:
1. git clone https://github.com/DVPeshe/Coaching.git
2. cd Coaching
3. mvn clean install
4. sudo docker-compose up -d
5. Откыть в браузере http://localhost:3000/market-front

Использованные технологии:

* Java
* Spring Boot
* Maven
* Spring Cloud Gateway
* Spring Web Service
* Spring Security
* PostgreSQL
* Flyway Migration
* Redis
* Lombok
* Swagger
* Docker
* Spring Data JPA
* JUnit

