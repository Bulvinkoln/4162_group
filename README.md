# **Создать веб проект**
## **Что такое Git?**
Git — это распределённая система управления версиями: есть один сервер, через который разработчики обмениваются кодом. Разработчик копирует (клонирует) проект к себе на локальную машину, делает изменения и сохраняет их на удалённый сервер. При необходимости другие разработчики могут скопировать эти изменения к себе.

## **Подготовка репозитория**
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## **Создание коммитов**
## Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*
## Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.
## Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.
## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*
## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием
## **Ветки в Git**
## Создание ветки
Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*
## Слияние веток
Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*
## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

## **Форк (Fork)**

Форк (Fork) — собственное ответвление (fork) какого-то проекта. Это означает, что GitHub создаст вашу собственную копию проекта, данная копия будет находиться в вашем пространстве имён, и вы сможете легко делать изменения путём отправки (push) изменений.

## **Пул-реквест — pull request PR**
Пул-реквест — pull request PR (пиар, он же merge request MR(мр)) — предложение изменения кода в чужом репозитории. Допустим, вы забрали к себе чужой репозиторий, поработали с ним и теперь хотите, чтобы ваши изменения попали в оригинальный репозиторий — тогда вы создаёте создаёте PR с просьбой добавить ваши изменения в репозиторий.

### 4162_group
