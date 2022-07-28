# Changelog

## [1.1.0](https://github.com/getCompass/userbot/releases/tag/v1.1.0)

- Добавлена новая версия Userbot API (версия 2).
- Изменён формат параметра user_id: ранее используемый как "User-{ID}" теперь принимает int-значение.
- На URL-адрсе установленного webhook параметр user_id также передаётся в формате int-значения.
- Добавлены новые методы: [webhook/setVersion](https://github.com/getCompass/userbot#post-webhooksetversion) и [webhook/getVersion](https://github.com/getCompass/userbot#post-webhookgetversion).
