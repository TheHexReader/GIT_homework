# 3 - Работа с ветками и тэгами

1. Создать проект в github - `introduction-3`
2. Склонировать его при помощи `git clone`
3. Создать в папке проекта README.md c текстом "Репозиторий с ветками и тэгами"
4. Добавить файл при помощи `git add README.md`
5. Сделать коммит с названием `git commit -m "Добавил README.md"`
6. Добавить тэг при помощи `git tag -a "V0" -m "Версия 0"`
7. Запушить комит и тэг на GitHub `git push --follow-tags`
---
8. Создать ветку и перейти на неё с помощью команды `git checkout -b feature`
9. Создать пустой файл с названием `feature1.txt`
10. Добавить файл при помощи `git add feature1.txt`
11. Сделать коммит с названием `git commit -m "Добавил фичу feature1.txt"`
12. Запушить и коммит и ветку на Github `git push --set-upstream origin feature`
---
13. Перейти на ветку `main` командой `git checkout main`
14. Слить ветку `feature` в ветку `main` командой `git merge feature`
15. Добавить тэг при помощи `git tag -a "V0.1" -m "Версия 0.1"`
16. Запушить слияние веток и тэг на GitHub `git push --follow-tags`
---
12. Перейти обратно на ветку `feature` при помощи `git checkout feature`
13. Создать и перейти на ветку `hotFix` при помощи `git checkout -b hotFix`
14. Создать пустой файл с названием `hotFix1.txt`.
15. Добавить файл при помощи `git add hotFix1.txt`
16. Сделать коммит с названием `git commit -m "Добавил фикс hotFix1.txt"`
17. Запушить коммит на Github `git push --set-upstream origin hotFix`
---
18. Перейти на ветку `main` командой `git checkout main`
19. Слить ветку `hotFix` в ветку `main` командой `git merge hotFix`
20. Добавить тэг при помощи `git tag -a "V0.1.1" -m "Версия 0.1.1"`
21. Запушить слияние веток и тэг на GitHub `git push --follow-tags`
---

## Пример выполненого задания

Репозиторий - [Introduction-3](https://github.com/TheHexReader/introduction-3)