##### 1. Реализовать REST API с OpenAPI спеком со следующим функционалом

- 1.1. Получение курса валют на стороннем API (RUB / EUR / USD / JPY). (например: https://currencyfreaks.com/)
    - 1.1.1. Если за текущий день не было курса, получить
    - 1.1.2. в 12:00 обновить курс валют
    - 1.1.3. Реализовать сохранение курса валюты в БД (MongoDB)

* 1.2. Реализовать эндпоинты:
    - 1.2.1. Получение курсов по указанной дате (все 4 валюты)
    - 1.2.2. Получение валютных пар из указанных 4х. Т.е. хочу получить курс Рубля к Йене или Доллар к Евро и т.д.

- 1.3. Реализовать валидацию запросов (даты, тикеров валют)
* 1.4. Реализовать доступ к API через API key
- 1.5. Реализовать логирование в БД запросов к API. Сохраняем в логи - дату, вид запроса (по дате / по паре)
* 1.6. Использовать для проекта docker.
- 1.7. При инициализации сервера заполнить БД первоначальными данными курсов валют по нескольким датам (значения любые)
* 1.8. Сделать возможность кросс-доменных запросов

При проверке тестового, кроме реализации прописанных пунктов, будет обращено внимание на:
- стиль кода
- логическую структуру проекта 
- соблюдение определенных стандартов (например конфигурация проекта)
- корректную реализацию выбранных решений
