## Описание
**Одиночка** — это порождающий паттерн проектирования, который гарантирует, что у класса
есть только один экземпляр, и предоставляет к нему глобальную точку доступа.

Одиночка решает сразу две проблемы, нарушая принцип единственной ответственности класса.
* **Гарантирует наличие единственного экземпляра класса**.
Чаще всего это полезно для доступа к какому-то общему ресурсу, например, базе данных.
* **Предоставляет глобальную точку доступа**.
Это не просто глобальная переменная, через которую можно достучаться к определённому объекту. Глобальные переменные не защищены от записи, поэтому любой код может подменять их значения без вашего ведома.

## Ссылки
* [refactoring.guru](https://refactoring.guru/ru/design-patterns/singleton)
