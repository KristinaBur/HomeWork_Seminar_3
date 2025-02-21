# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
<span style="color:blue">**Git**</span> - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория

Для создание репозитория необходимо выполнить команду <span style="color:blue">**git init**</span> в папке с репозиторием и у Вас создастся репозиторий (появится скрытая папка .git).

## Создание коммитов

<span style="color:blue">**Git add**</span>
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*.

<span style="color:MediumPurple">*Просмотр состояния репозитория.*</span>
Для того, чтобы посмотреть состояние репозитория используется команда <span style="color:blue">**git status**</span>. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

<span style="color:MediumPurple">*Создание коммитов*.</span>
Для того, чтобы создать коммит (сохранение) необходимо выполнить команду <span style="color:blue">**git commit**</span>. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

<span style="color:MediumPurple">*Перемещение между сохранениями*.</span>
Для того, чтобы перемещаться между коммитами, используется команда <span style="color:blue">**git checkout**</span>. Используется она в папке с репозиторием следующим образом: *git checkout <номер коммита>*.

<span style="color:MediumPurple">*Журнал изменений*.</span>
Для того, чтобы посмотреть все сделанные изменения в репозитории, используется команда <span style="color:blue">**git log**</span>. Для этого достаточно выполнить команду *git log* в папке с репозиторием.

## Ветки в Git:
<span style="color:Gold">- *Создание ветки*.</span>

Для того, чтобы создать ветку, используется команда <span style="color:Khaki">- *git branch*.</span> Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*.

<span style="color:Gold">- *Слияние веток*.</span>

Для того чтобы дабавить ветку в текущую ветку используется команда <span style="color:Khaki">- *git merge</span>  <наименование ветки>*.

<span style="color:Gold">- *Удаление веток*.</span>
Для удаления ветки ввести команду <span style="color:Khaki">- *"git branch -d 'name branch'"*</span>.

# <p style="text-align: center;"> Спасибо за просмотр!</p>
![foto](https://klike.net/uploads/posts/2019-06/1560329641_2.jpg)

> [P.s. Полезные советы - работа с языком Markdown](https://lifehacker.ru/chto-takoe-markdown/)