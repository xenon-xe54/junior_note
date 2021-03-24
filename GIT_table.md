# Git-команды в таблице

| № | Назначение команды | Команда | Пример |
|---|---|---|---|
| 1 | Клон репо из своего форка | `git clone <ssh-key-repo>` |`git clone git@github.com:username/repo.git`|
| 2 | Переход в папку локального репо | `cd <folder-name>` |  |
| 3 | Создание новой ветки с переходом на неё | `git checkout -b <branch-name>` |  |
| 4 | Проверяем ветки | `git branch` |  |
| 5 | Проверяем ремоуты | `git remote -v` |  |
| 6 | Добавляем ремоут | `git remote add <remote-name> <ssh-key-remote-repo>` | `git remote add upstream git@github.com:username/repo.git`|
| 7 | Проверяем изменения | `git status` |  |
| 8 | Добавляем изменения |`git add <file-name>` |`git add Readme.md`|
| 8.1 | Добавляем все изменения | `git add .` | |
| 9 | Сохраняем изменения | `git commit -m "commit-message"` | `git commit -m "First commit"` |
| 10 | Отправить изменения в гит вместе с веткой | `git push origin <branch-name>` | `git push origin example-branch` |
| 11 | Переключись на мастер | `git checkout master` | |
| 12 | Стянуть все изменения из оригинального репо | `git pull <parent-repo> <branch>` | `git pull upstream master` |
| 13 | Обновить форк | `git push origin <branch>` |  | 