# H1 Шпаргалка. 
## H2 Базовые команды в консоли
##### H5 Навигация
* pwd (от англ. _print working directory_, «показать рабочую папку») — покажи, в какой я папке;
* ls (от англ. _list directory contents_, «отобразить содержимое директории») — покажи файлы и папки в текущей папке;
* ls -a — покажи также скрытые файлы и папки, названия которых начинаются с символа .;
* cd first-project (от англ. _change directory_, «сменить директорию») — перейди в папку first-project;
* cd first-project/html — перейди в папку html, которая находится в папке first-project;
* cd .. — перейди на уровень выше, в родительскую папку;
* cd ~ — перейди в домашнюю директорию (/Users/Username);
* cd / — перейди в корневую директорию.
##### H5 Работа с файлами и папками
###### H6 Создание
* touch index.html (англ. _touch_, «коснуться») — создай файл index.html в текущей папке;
* touch index.html style.css script.js — если нужно создать сразу несколько файлов, можно напечатать их имена в одну строку через пробел;
* mkdir second-project (от англ. _make directory_, «создать директорию») — создай папку с именем second-project в текущей папке.
###### H6 Копирование и перемещение
* cp file.txt ~/my-dir (от англ. _copy_, «копировать») — скопируй файл в другое место;
* mv file.txt ~/my-dir (от англ. _move_, «переместить») — перемести файл или папку в другое место.
###### H6 Чтение
* cat file.txt (от англ. concatenate and print, «объединить и распечатать») — распечатай содержимое текстового файла file.txt.
###### H6 Удаление
* rm about.html (от англ. _remove_, «удалить») — удали файл about.html;
* rmdir images (от англ. _remove directory_, «удалить директорию») — удали папку images;
* rm -r second-project (от англ. _remove_, «удалить» + _recursive_, «рекурсивный») — удали папку second-project и всё, что она содержит.
##### H5 Полезные возможности
Команды необязательно печатать и выполнять по очереди. Можно указать их списком — разделить двумя амперсандами (__&&__).
У консоли есть собственная память — буфер с несколькими последними командами. По ним можно перемещаться с помощью клавиш со стрелками вверх (__↑__) и вниз (__↓__).
Чтобы не вводить название файла или папки полностью, можно набрать первые символы имени и дважды нажать Tab. Если файл или папка есть в текущей директории, командная строка допишет путь сама.
Например, вы находитесь в папке dev. Начните вводить __cd first__ и дважды нажмите Tab. Если папка first-project есть внутри dev, командная строка автоматически подставит её имя. Останется только нажать __Enter__.
