# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

---
## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

### Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

### Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

---
## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

### Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

### Удаление веток
Для удаления ветки ввести команду *"git branch -d 'name branch'"*

---
## Добавление картинок
Для того чтобы добавить **картинку** надо: 
![Картинка](https://static.tildacdn.com/tild6365-3833-4231-b931-373730316430/baikal_1.jpg)
![picture](https://fun-cats.ru/wp-content/uploads/2/9/d/29d7df2bf153b909e1dba4142a2bc4e6.jpeg)

---
## Добавление ссылки
Для того, чтобы добавить **ссылку**, надо: [Работа с языком](https://yandex.ru/turbo/lifehacker.ru/s/chto-takoe-markdown/)

--- 
## Добавление цитат и списков
Для того, чтобы добавить **ненумерованный список** надо:
* первая строка
* втроая строка
- первая строка
- втроая строка
+ первая строка
+ втроая строка

Для того, чтобы добавить **нумерованный список** надо:
1. четвертая строка
2. пятая строка
3. шестая строка

* чтобы добавить *одиночную* цитату, надо постачить знак ">"
>Да прибудет с тобой сила

>Если бы ты не мог проснуться, как бы ты узнал, что сон, а что действительность?

* Чтобы поставить *цитату с цитатой*, надо поставить ">>"

> Мы ходим на работу, которую ненавидим, чтобы купить барахло, которое нам не нужно.
>> Мы работаем в дерьме, чтобы купить дерьмо. (Бойцовский клуб)
---