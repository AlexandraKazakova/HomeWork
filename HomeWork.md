# ***<font color = 0000CD>Инструкция для работы с Git и удалёнными репозиториями*** </font>

***

## <font color = 000080> *Что такое Git?* </font>

<img src="image1.jpeg" width="200" height="100" alt="pic.1">

*Git* - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## <font color = 4169E1> *Подготовка репозитория* </font>

Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git).

## <h2 style="color:#4169E1"> *Создание коммитов*

* ### <h3 style="color:#1E90FF"> *Git add*

Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*.

* ### <h3 style="color:#1E90FF"> *Git status*

Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

* ### <h3 style="color:#1E90FF"> *Git commit*

Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*.

!!! important Все файлы для коммита должны быть ***<font color = FF0000>ДОБАВЛЕНЫ*** </font> и сообщение к коммиту писать ***<font color = FF0000>ОБЯЗАТЕЛЬНО***</font>.

* ### <h3 style="color:#1E90FF"> *Git checkout*

Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*.

## <h2 style="color:#4169E1"> *Журнал изменений*

Для того, чтобы посмотреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием.

## <h2 style="color:#4169E1"> *Ветки в Git*

* ### <h3 style="color:#00CED1"> *Создание ветки*

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*.

* ### <h3 style="color:#00CED1"> *Слияние веток*

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <название ветки>*.

* ### <h3 style="color:#00CED1"> *Удаление веток*

Для удаления ветки ввести команду "git branch -d 'name branch'".

!!! note <font style="color:#000080"> *Шпаргалка* </font>
    | <font style="color:#000080"> Команда | <font style="color:#000080"> Назначение |
    |--|--|
    | <font style="color:#FF0000"> git init | инициализация локального репозитория |
    | <font style="color:#FF0000"> git status | информация о текущем состоянии |
    | <font style="color:#FF0000"> git add | добавить файл |
    | <font style="color:#FF0000"> git commit -m "..."| создание коммита |
    | <font style="color:#FF0000"> get log | вывод истории коммитов |
    | <font style="color:#FF0000"> git checkout | переход к другому коммиту |
    | <font style="color:#FF0000"> get checkout master | вернуться к актуальному состоянию |
    | <font style="color:#FF0000"> git diff | разница текущего и закомиченного |
    | <font style="color:#FF0000"> git config --list | показать все надстройки |
    | <font style="color:#FF0000"> git branch "..." | создать новую ветку |
    | <font style="color:#FF0000"> git merge | слияние веток |
    | <font style="color:#FF0000"> git branch -d "..." | удаление веток|
    | <font style="color:#FF0000"> git merge --abort | прервет слияние |
    | <font style="color:#FF0000"> git merge --continue | продолжит слияние |
    | <font style="color:#FF0000"> git checkout --ours | выбрать файл папки main/master |
    | <font style="color:#FF0000"> git checkout --their | выбрать файл из ветки |

!!! note <font style="color:#000080"> *Полезные ссылки для для GIT и Markdown*
    [Github](https://github.com/sandino/Markdown-Cheatsheet)
    [Microsoft](https://docs.microsoft.com/ru-ru/contribute/markdown-reference)
    [Краткое руководство](https://paulradzkov.com/2014/markdown_cheatsheet/)
    [Полезные Расширения](https://coderscat.com/awesome-vscode-extensions-for-markdown/)
