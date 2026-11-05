# Задание 4: Пример API-запроса

В качестве примера описан запрос на авторизацию пользователя.

**Описание:** Запрос отправляет учетные данные пользователя на сервер для получения токена авторизации.

### Параметры запроса:

*   **Метод:** `POST`
*   **URL:** `https://stellantis.autocrm.ru/api/auth/login` *(предполагаемый эндпоинт)*
*   **Headers:**
    *   `Content-Type: application/json`
    *   `Accept: application/json`
*   **Body:**

```json
{
  "email": "romaspb888@gmail.com",
  "password": "111"
}
