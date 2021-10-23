# vk-actions-notify
🤖 Уведомления ВКонтакте для Github Actions

## Входные данные

### `token`
**Обязательно**.
Токен доступа к сообществу, откуда будет отправлено сообщение. Требуемые права: `messages`.

### `peer_id`
**Обязательно**.
`peer_id` чата, куда будет отправлено сообщение.

### `message`
Сообщение, которое будет отправлено. По умолчанию генерируется.

## Пример
```yaml
# ...
uses: cteamdev/vk-actions-notify@v1
  with:
    token: # ...
    peer_id: # ...
```

## Спасибо
Сделано на примере [alphamusic/VK-Notifications](https://github.com/alphamusic/VK-Notifications).