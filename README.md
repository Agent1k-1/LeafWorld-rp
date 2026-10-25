# LeafWorld Resource Pack

Ресурс-пак с логотипом LeafWorld без нижнего подчёркивания для TAB и скорборда Minecraft Java Edition.
Метаданные совместимости: 1.21.4–1.21.11; в игровом клиенте не тестировался.

[Скачать ZIP](https://github.com/Agent1k-1/LeafWorld-rp/raw/refs/heads/main/LeafWorld-RP-1.21.4-plus.zip)

## Unicode

- TAB: `` — U+E001, для legacy-форматирования: `&f`
- Скорборд: `` — U+E002, для legacy-форматирования: `&f`

Белый цвет сохраняет цвета изображения. Вставьте символы в настройки вашего плагина TAB/скорборда. Игрок должен принять ресурс-пак.

## server.properties

```properties
resource-pack=https://raw.githubusercontent.com/Agent1k-1/LeafWorld-rp/main/LeafWorld-RP-1.21.4-plus.zip
resource-pack-sha1=98e32e39d3c579b37d6112f79beab26519a12def
require-resource-pack=true
```

Перезапустите сервер после изменения настроек. Для закрытого репозитория потребуется публичный хостинг ZIP: игровые клиенты должны скачивать файл без авторизации.

Подробности: [инструкция](LeafWorld-setup.txt), [символы](LeafWorld-Unicode.txt).
