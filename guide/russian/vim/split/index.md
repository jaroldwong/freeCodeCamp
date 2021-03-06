---
title: Split
localeTitle: Трещина
---
# Открытие файлов в Vim с помощью Split

В Vim файлы можно открыть или `split` горизонтали и вертикали, чтобы создать дополнительное окно или окно просмотра для данного файла.

### Командные клавиши

Команды для создания горизонтального разделения:

: `[N]split` `[file]`

: `[N]sp` `[file]`

где `sp` - короткая аббревиатура для `split` .

Команды для создания вертикального разделения:

: `[N]vsplit` `[file]`

: `[N]vs` `[file]`

где `vs` - короткая аббревиатура для `vsplit` и ...

*   `[N]` - высота (по умолчанию используется окно с половинным током).
*   `[file]` - это файл, который нужно открыть в новом окне разделения (текущий файл используется, если он не указан).

### Примеры

Некоторые примеры использования split в Vim:

*   : `sp` Разделить текущее окно на равные горизонтальные окна для текущего файла.
*   : `10sp` Разбить текущее окно, создав новое окно с высотой 10 для текущего файла.
*   : `sp` `index.html` Разделите текущее окно на равные горизонтальные окна и откройте `index.html` в новом окне.
*   : `vs` `main.css` Разделите текущее окно на равные вертикальные окна и откройте `main.css` в новом окне.