# База знаний
[Статус по темам](STATUS.md)

## [Базы данных](database)
* [Общее](database/common)
  * [CAP](database/common/cap.md) (Не готов)
  * [SQL vs NoSQL](database/common/sql-vs-no-sql.md) (Не готов)
* [Реляционные](database/relational/) (Не готов)
  * [ACID](database/relational/acid.md) (Не готов)
  * [Индексы](database/relational/indexes.md) (Не готов)
  * [Нормализация / Денормализация](database/relational/normal.md) (Не готов)
  * [Транзакции](database/relational/transactions.md) (Не готов)
    * Изоляции (Не готов)
    * Блокировки (Не готов)
* [NoSQL](database/no-sql) (Не готов)
  * [Redis](database/no-sql/redis.md) (Не готов)
  * [MongoDB](database/no-sql/mongo-db.md) (Не готов)


## [Общее](common)
* [ООП](common/oop.md) (В процессе)
* [SOLID](common/solid.md) (Не готов)
* [Архитектурные паттерны](common/architecture-patterns)
  * [MVC](common/architecture-patterns/mvc.md) (В процессе)
* [Структурные паттерны](common/structure-patterns) (В процессе)
* [Методологии разработки](common/methodology)
  * [TDD](common/methodology/tdd.md) (Не готов)
    * [Пример сервиса](common/methodology/tdd-service)
  * [DDD](common/methodology/ddd.md) (Не готов)
    * [Пример сервиса](common/methodology/ddd-service)

## [Web](web)
* [REST](web/rest.md) (Не готов)
* [GraphQL](web/graphql.md) (В процессе)
  * [Пример сервиса](web/graphql-service)
* [RPC](web/rpc.md) (Не готов)
  * [Пример сервиса](web/rpc-service)
* [Socket](web/socket.md) (Не готов)
* [Polling](web/polling.md) (Не готов)
* [HTTP](web/http.md) (Не готов)
  * [HTTP/2 сервис](web/http2.0-service)
* [CORS](web/cors.md) (Не готов)
* [Throttle](web/throttle.md) (Не готов)
  * Debouncing

## [Безопасность](security)
* [JWT](security/jwt.md) (Не готов)
* [SSL](security/ssl.md) (Не готов)
* [CSRF](security/csrf.md) (Не готов)
* [SQL-инъекции](security/sql-injections.md) (Не готов)

## [Python](python)
* [Общее](python/common)
  * [Асинхронность](python/common/async.md) (Проверен)
  * [Мультипоточность](python/common/threading)
    * [GIL](python/common/threading/gil.md) (Проверен)
  * [Генераторы](python/common/generators.md) (Проверен)
  * [Декораторы](python/common/decorators.md) (Ревью)
  * [Контекстные менеджеры](python/common/context-manager.md) (Ревью)
  * [Функциональные элементы](python/common/functional.md) (Не готов)
  * [Классы](python/common/classes)
    * Наследование (Не готов)
    * [Абстрактные классы](python/common/classes/abstract_base_classes.md) (Ревью)
    * [Метаклассы](python/common/classes/metaclasses.md) (Ревью)
    * [Датаклассы](python/common/classes/dataclasses.md) (Проверен)
    * Методы (Не готов)
* [Производительность](python/perfomance)
  * [Память](python/perfomance/memory.md) (В процессе)
  * [Общее](python/perfomance/init.md) (В процессе)
  * [Иммутабельность](python/perfomance/immutables.md) (В процессе)
  * [C-расширения](python/perfomance/c.md) (В процессе)
  * [Стандартные решения](python/perfomance/standart.md) (В процессе)
* [Сахар](python/sugar.md) (В процессе)
* [Справка по версиям](python/versions)
  * [3.7](python/versions/3.7.md) (На ревью)
  * [3.8](python/versions/3.8.md) (На ревью)
  * [3.9](python/versions/3.9.md) (На ревью)
  * [3.10](python/versions/3.10.md) (На ревью)
  * [3.11](python/versions/3.11.md) (На ревью)

## [Брокеры сообщений](brokers)
* [Общее](brokers/common.md) (На ревью)
* [RabbitMQ](brokers/rabbitmq.md) (В процессе)
  * [Exchanges](brokers/rabbitmq/exchanges.md) (Проверен)
* [Kafka](brokers/kafka.md) (В процессе)