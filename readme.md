# testGit
**Залить изминения на git 
    1) git add . - пометить файлы, которые надо залить
    2) git commit -m " " - подтвердить выделенные файлы
    3) git push origin <branch-name> - загрузить изменения на удаленную ветку
**Загрузить измения с репозитория 
    1) git pull origin <branch-name>
** Спрятать/достать изменения
    1) git stash (pop)
** Создание новой ветки 
    1) git checkout -b <branch-name>
** Переключение между ветками
    1) git checkout <branch-name>
** Слияние веток 
    1) две ветки А и Б
    2) находимся на А
    3) хотим чтобы на ветки А были изменения с ветки Б
    4) выполняем команду: git merge <Б-name> (git rebase <Б-name>)
