# :train2: Учебная работа "Путешествия по России"

GitHub Pages :point_right: https://aleksdsgn.github.io/russian-travel/

Проект о путешествиях по стране. Это одностраничный сайт с атмосферными изображениями и описанием интересных мест в России. На сайте есть ссылки на информацию об упоминаемых местах. Также полезные ссылки на ресурсы которые могут пригодиться при самостоятельном планировании путешествия.

В этом проекте реализована адаптивная верстка. Использована продвинутая семантика языка HTML[^1]. Код проверен на валидность[^2]. Изображения оптимизированы [^3]

Используются технологи **HTML5** и **СCS3**.
Была создана структура по правилам **[Nested БЭМ](https://ru.bem.info/methodology/filestructure/#nested)**[^4].
Для построения сеток некоторых блоков используется технология CSS Grid Layout.
Для других блоков используется CSS Flex.

Посмотреть проект "вживую" на GitHub Pages :point_right: ["Путешествия по России"](https://aleksdsgn.github.io/russian-travel/)

[^1]: Использование элементов структурной семантики `<header>`, `<main>`, `<section>`, `<figure>`, `<article>`, `<nav>` и `<footer>`.
[^2]: Проверено на https://validator.w3.org/nu/.
[^3]: Сжаты при помощи сервиса [TinyPNG](https://tinypng.com/).
[^4]: Классическая схема организации файловой структуры БЭМ-проектов: блоку соответствует одна директория; код модификаторов и элементов находится в отдельных файлах;  файлы модификаторов и элементов хранятся в отдельных директориях; директория блока является корневой для поддиректорий его элементов и модификаторов; имена директорий элементов начинаются с двойного подчеркивания(__); имена директорий модификаторов начинаются с одинарного подчеркивания (_).
