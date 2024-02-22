<h1>Создание простого RESTful сервиса для управления книгами</h1>

---
***Сущность "Книга" содержит следующие атрибуты:***

- ID (уникальный идентификатор)
- Название
- Автор
- Год издания
---


***Интерфейс BookRepository, наследующий JpaRepository, для работы с сущностями книги***

***Cервис BookService, который будет взаимодействовать с репозиторием для выполнения операций CRUD***

***Класс BookController с аннотацией @RestController. Контроллере методы для обработки HTTP-запросов: GET (получение списка книг и получение книги по ID), POST (добавление новой книги), PUT (обновление существующей книги), DELETE (удаление книги по ID)***

