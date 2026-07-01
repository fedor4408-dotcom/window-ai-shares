# AI quick start index

Это главный входной файл для AI. Используйте его вместо ZIP: все ссылки ведут на публичные raw-файлы пакета.

## Задача пользователя

**Название:** Задача без названия

**Инструкция:** дать итоговые цены на шкафы в чат с учетом хуавей

**Ожидаемый формат ответа:** Не указан.

**Ограничения и заметки:** Нет.

## Быстрый порядок чтения

1. Прочитайте [task/task.md](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/task/task.md).
2. Проверьте состав пакета в [manifest.json](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/manifest.json).
3. Сначала откройте crop-файлы из раздела «Главные выделения пользователя». Это наиболее важные фрагменты.
4. Если нужны исходные документы, откройте файлы из раздела «Исходные файлы».
5. Если исходный PDF/Word/Excel не читается напрямую, используйте связанные скриншоты, crop-файлы и metadata.
6. Сформируйте ответ строго по задаче пользователя. Не выдумывайте недостающие факты.

## Главные выделения пользователя

| # | Скриншот | Комментарий пользователя | Crop | Полный скриншот | Metadata | Координаты |
|---|---|---|---|---|---|---|
| 1 | screenshot-1 | найти цены в интернете | [crop](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/linked-screenshots/screenshot-1/crops/annotation-1.png) | [source image](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/linked-screenshots/screenshot-1/image.png) | [metadata](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/linked-screenshots/screenshot-1/metadata.json) | x=12, y=642, w=700, h=135 |
| 2 | screenshot-2 | добавить хуавей к каждому шкафу | [crop](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/linked-screenshots/screenshot-2/crops/annotation-1.png) | [source image](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/linked-screenshots/screenshot-2/image.png) | [metadata](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/linked-screenshots/screenshot-2/metadata.json) | x=16, y=126, w=984, h=600 |
| 3 | screenshot-3 | контекст по нему ответным письмом отправляем игорю ответ с ценами на шкафы с учетом хуавей | [crop](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/standalone-screenshots/screenshot-3/crops/annotation-1.png) | [source image](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/standalone-screenshots/screenshot-3/image.png) | [metadata](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/standalone-screenshots/screenshot-3/metadata.json) | x=6, y=8, w=1538, h=771 |

## Исходные файлы

| ID | Тип | Имя | Файл | Metadata | Связанные скриншоты |
|---|---|---|---|---|---|
| file-1 | excel | Заказ клиента (GIT) № 4021 от 30.06.2026.xlsx | [original](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/files/file-1/original/GIT-No-4021-30.06.2026.xlsx) | [metadata](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/files/file-1/metadata.json) | screenshot-1, screenshot-2 |

## Скриншоты

| ID | Тип связи | Имя | Размер | Изображение | Metadata | Связанный файл | Аннотаций |
|---|---|---|---|---|---|---|---|
| screenshot-1 | linked_to_file | image.png | 1553x871 | [image](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/linked-screenshots/screenshot-1/image.png) | [metadata](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/linked-screenshots/screenshot-1/metadata.json) | Заказ клиента (GIT) № 4021 от 30.06.2026.xlsx | 1 |
| screenshot-2 | linked_to_file | image.png | 1566x825 | [image](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/linked-screenshots/screenshot-2/image.png) | [metadata](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/linked-screenshots/screenshot-2/metadata.json) | Заказ клиента (GIT) № 4021 от 30.06.2026.xlsx | 1 |
| screenshot-3 | standalone_context | image.png | 1562x787 | [image](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/standalone-screenshots/screenshot-3/image.png) | [metadata](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/standalone-screenshots/screenshot-3/metadata.json) | нет | 1 |

## Служебные файлы

- [README_FOR_AI.md](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/README_FOR_AI.md) - описание структуры пакета.
- [task/task.json](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/task/task.json) - задача в JSON.
- [manifest.json](https://raw.githubusercontent.com/fedor4408-dotcom/window-ai-shares/main/latest/manifest.json) - машинное описание состава пакета.

## Сводка пакета

- Версия пакета: 0.2
- Создан: 2026-07-01T14:35:48.406Z
- Исходных файлов: 1
- Связанных скриншотов: 2
- Самостоятельных скриншотов: 1
- Аннотаций: 3
