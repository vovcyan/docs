# Формат ответа

Ответ может содержать:
- Результат выполнения запроса в случае успеха.
- Код и описание ошибки, если в результате запроса произошла ошибка:
  ```json
  {
    "error_code": "{string}",
    "error_message": "{string}"
  }
  ```

## Коды ответа {#response-codes}

Код | Причина | Описание
----- | ----- | -----
200 | OK | Запрос выполнен успешно.
400 | BAD_REQUEST | Синтаксическая ошибка в запросе.
401 | UNAUTHORIZED | Ошибка авторизации.
429 | TOO_MANY_REQUESTS | Превышен лимит запросов.
500 | INTERNAL_SERVER_ERROR | Ошибка на стороне сервера.


