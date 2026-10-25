# LeafWorld Resource Pack

Ресурс-пак с логотипом LeafWorld без нижнего подчёркивания для TAB, скорборда и заголовка меню ESC Minecraft Java Edition.
Метаданные совместимости: 1.21.4–1.21.11; в игровом клиенте не тестировался.

[Скачать ZIP](https://github.com/Agent1k-1/LeafWorld-rp/raw/refs/heads/main/LeafWorld-RP-1.21.4-plus.zip)

## Меню ESC

В русском и английском интерфейсе заголовок меню паузы заменён на логотип LeafWorld через перевод `menu.game`. Плагины не требуются; кнопки остаются прежними. Моды интерфейса могут переопределять заголовок.

## Unicode

- TAB: `` — U+E001, для legacy-форматирования: `&f`
- Скорборд: `` — U+E002, для legacy-форматирования: `&f`

Логотипы TAB и скорборда уменьшены на 25%; размер логотипа ESC сохранён отдельным символом U+E003.

Белый цвет сохраняет цвета изображения. Вставьте символы в настройки вашего плагина TAB/скорборда. Игрок должен принять ресурс-пак.

## server.properties

```properties
resource-pack=https://raw.githubusercontent.com/Agent1k-1/LeafWorld-rp/main/LeafWorld-RP-1.21.4-plus.zip
resource-pack-sha1=8c145868f78535ebf36cba66b58af538d31fc84a
require-resource-pack=true
```

Перезапустите сервер после изменения настроек. Для закрытого репозитория потребуется публичный хостинг ZIP: игровые клиенты должны скачивать файл без авторизации.

Подробности: [инструкция](LeafWorld-setup.txt), [символы](LeafWorld-Unicode.txt).
