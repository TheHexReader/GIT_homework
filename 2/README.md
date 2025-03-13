# 2 - Работа с ветками

1. Создать проект в github - `introduction-2`
2. Склонировать его при помощи `git clone`
3. Создать в папке проекта README.md c текстом "Репозиторий с ветками"
4. Добавить файл при помощи `git add README.md`
5. Сделать коммит с названием `git commit -m "Добавил README.md"`
6. Запушить комит на GitHub `git push`
---
7. Создать ветку и перейти на неё с помощью команды `git checkout -b other`
8. Создать пустой файл с названием `other.txt`
9. Добавить файл при помощи `git add other.txt`
10. Сделать коммит с названием `git commit -m "Добавил файл other.txt на ветку other"`
11. Запушить и коммит и ветку на Github `git push --set-upstream origin other`
---
12. Перейти обратно на ветку `main` при помощи `git checkout main`
13. Создать пустой файл с названием `main.txt`.
14. Добавить файл при помощи `git add main.txt`
15. Сделать коммит с названием `git commit -m "Добавил файл main.txt на ветку main"`
16. Запушить коммит на Github `git push`
---
17. Слить две ветки `other` в `main` при помощи `git merge other`
18. Запушить слияние веток в GitHub `git push`



## Пример выполненого задания

Репозиторий - [Introduction-2](https://github.com/TheHexReader/introduction-2)