# Changelog

## [Api V3](https://github.com/getCompass/userbot/releases/tag/master)

- Добавлена новая версия Userbot API (версия 3). 
- Все запросы в Userbot API выполняются синхронно и сразу возвращают результат своего выполнения.
- Удалён API-метод /request/get.
- Изменён способ авторизации запросов к Userbot API - header-заголовок Signature удалён из проекта. Теперь для авторизации запроса необходимо передавать только header-заголовок Authorization.
- Изменился список системных ошибок - удалена ошибка "Некорректная подпись для валидации переданных данных".
- Запрос, отправляемый на webhook, теперь содержит только header-заголовок Authorization. 
- Добавилась возможность синхронного ответа на запрос, пришедший на ваш webhook.

## [Api V2](https://github.com/getCompass/userbot/releases/tag/v2)

- Добавлена новая версия Userbot API (версия 2).
- Реализован новый способ авторизации запросов к Userbot API.
- Изменён формат параметра user_id: ранее используемый как "User-{ID}" теперь принимает int-значение.
- На URL-адрес установленного webhook параметр user_id также передаётся в формате int-значения.
- Добавлены новые API-методы: [webhook/setVersion](https://github.com/getCompass/userbot#post-webhooksetversion) и [webhook/getVersion](https://github.com/getCompass/userbot#post-webhookgetversion).

## [Userbot release](https://github.com/getCompass/userbot/releases/tag/v1)

- Реализованы чат-боты Compass.
