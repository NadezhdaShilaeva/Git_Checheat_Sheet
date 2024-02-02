# Шпаргалка по Git

###### Выполнено по курсу ["Основы работы с git"](https://practicum.yandex.ru/git-basics/) от Яндекс Практикум


**Система контроля версий**, или **VCS**, — это программное обеспечение, которое помогает отслеживать изменения в программах, текстовых файлах, больших документах, веб-сайтах и так далее. 

**Git** — один из примеров системы контроля версий: он позволяет хранить, изменять и анализировать историю проекта. Это программа, которая в том числе может работать из *командной строки*. Любой графический интерфейс для Git всего лишь преобразует клики пользователя в вызовы программы.

**Командная строка** (англ. *Command-line Interface*, или *CLI*) — текстовый интерфейс. Пользователь вводит в неё команды. Она принимает их от пользователя и выполняет. Эта строка — обычная программа на компьютере.

## Шпаргалка. Базовые команды в консоли

### Навигация
* ```pwd``` (от англ. *print working directory*, «показать рабочую папку») — покажи, в какой я папке;
* ```ls``` (от англ. *list directory contents*, «отобразить содержимое директории») — покажи файлы и папки в текущей папке;
* ```ls -a``` — покажи также скрытые файлы и папки, названия которых начинаются с символа .;
* ```cd first-project``` (от англ. *change directory*, «сменить директорию») — перейди в папку ```first-project```;
* ```cd first-project/html``` — перейди в папку ```html```, которая находится в папке ```first-project```;
* ```cd ..``` — перейди на уровень выше, в родительскую папку;
* ```cd ~``` — перейди в домашнюю директорию (/Users/Username);
* ```cd /``` — перейди в корневую директорию.

### Работа с файлами и папками
#### Создание
* ```touch index.html``` (англ. *touch*, «коснуться») — создай файл ```index.html``` в текущей папке;
* ```touch index.html style.css script.js``` — если нужно создать сразу несколько файлов, можно напечатать их имена в одну строку через пробел;
* ```mkdir second-project``` (от англ. *make directory*, «создать директорию») — создай папку с именем ```second-project``` в текущей папке.
#### Копирование и перемещение
* ```cp file.txt ~/my-dir``` (от англ. *copy*, «копировать») — скопируй файл в другое место;
* ```mv file.txt ~/my-dir``` (от англ. *move*, «переместить») — перемести файл или папку в другое место.
#### Чтение
* ```cat file.txt``` (от англ. *concatenate and print*, «объединить и распечатать») — распечатай содержимое текстового файла ```file.txt```.
#### Удаление
* ```rm about.html``` (от англ. *remove*, «удалить») — удали файл ```about.html```;
* ```rmdir images``` (от англ. *remove directory*, «удалить директорию») — удали папку ```images```;
* ```rm -r second-project``` (от англ. *remove*, «удалить» + *recursive*, «рекурсивный») — удали папку ```second-project``` и всё, что она содержит.

### Полезные возможности
* Команды необязательно печатать и выполнять по очереди. Можно указать их списком — разделить двумя амперсандами (```&&```).

* У консоли есть собственная память — буфер с несколькими последними командами. По ним можно перемещаться с помощью клавиш со стрелками вверх (```↑```) и вниз (```↓```).

* Чтобы не вводить название файла или папки полностью, можно набрать первые символы имени и дважды нажать ```Tab```. Если файл или папка есть в текущей директории, командная строка допишет путь сама.

---

