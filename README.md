### Как сделать бекап данных vaultwarden

Основное, что нужно сохранить - база данных sqlite.

## Ручной режим

1. Подключитесь к серверу и запустите команду:

```
docker exec -it vaultwarden /vaultwarden backup
```

Ожидаемый результат:

```
Backup to 'data/db_20250609_085940.sqlite3' was successful
```

2. Скопируйте файл в хранилище бекапов
