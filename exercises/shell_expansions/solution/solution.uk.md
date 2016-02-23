# Чудово!

Ви щойно вивели структуру директорій,  але ви можете простіше створтти подібне дерево директорій схожим чином. Для цього існують команди `mkdir` та `touch`.

Команда `mkdir` створює порожню папку із переденим ім’ям. Команда `touch` створює файл із переданим ім’ям.

Тепер, коли ми знаємо про ці команди:

```bash
mkdir -p project/{src,dest,test}/
touch project/{src,dest,test}/{index,util}.js
```

Вище використаний пропорець `-p` разом із командою `mkdir` для створення батьківської директорії, якщо у цьому є потреба.

Для того щоб проглянути зміст директорій використовуйте команду `ls`.

Виконайте `man` для того щоб дізнатися більше про команди `mkdir`, `touch` та `ls`.

У наступному завданні Ви дізнаєтеся про streams, pipes та lists.