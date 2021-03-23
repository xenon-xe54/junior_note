# Git-памятка
_________________________

### Небольшая Пометка

Чтобы использовать нужно знать несколько вещей:

1. Это обращение к гиту. Оно есть везде и его не надо пропускать. 

    `git`
2. Сначала пишется команда, а потом в <> указывается пользовательский параметр, например название файла, ветки или репозитория

_______

## Сборник команд

1. Клон репо из своего гита
  
    `git clone <ssh-key-repo>`  
    *(Пример: `git clone git@github.com:username/repo.git`)*

2. Переход в репо
  
    `cd <folder-name>`

3. Создание новой ветки с переходом на неё
  
    `git checkout -b <branch-name>`

4. Проверяем ветки
  
    `git branch`

5. Проверяем ремоуты
  
    `git remote -v`

6. Добавляем ремоут
  
    `git remote add <remote-name> <ssh-key-remote-repo>`  
    *(Пример: `git remote add upstream git@github.com:username/repo.git`)*

7. Проверяем изменения
  
    `git status`

8. Добавляем изменения
  
    `git add <.>` *(Добавляет все файлы в текущей директории)*  
    `git add <file-name>` *(Добавляет файл с именем file-name)*

9. Сохраняем изменения
  
    `git commit -m "commit-message"`

10. Отправить изменения в гит вместе с веткой
  
    `git push origin <branch-name>`

11. Переключись на мастер
  
    `git checkout master`

12. Стянуть все изменения из оригинального репо
  
    `git pull <parent-repo> <branch>`  
    *(Пример: `git pull upstream master`)*

13. Обновить форк
  
    `git push origin <branch>`

## Перед началом работы

1. После всех принятых правок переключись на мастер

    `git checkout master`

2. Стягиваем все изменения из оригинального репо
  
    `git pull <parent-repo> <branch>`  
    *(Пример: `git pull upstream master`)*

3. Обновить форк
  
    `git push origin <branch>`

4. Создание новой ветки и переключение на неё
  
    `git checkout -b <branch-name>`

5. Удалить ненужную ветку
  
    `git branch -D <branch-name>`

6. Обновить форк
  
    `git push origin <branch>`

7. Проверяем ветки
  
    `git branch`

## При выполнении работы

1. Работаем над проектом
2. Проверяем изменения

    `git status`

3. Добавляем изменения

    `git add <. or file-name>`

4. Повторяем 2 пункт
5. Сохраняем изменения

    `git commit -m "commit-message"`

6. Поторяем пункт 2

## При поступлении исправлений

1. Работаем над проектом
2. Проверяем изменения

    `git status`

3. Добавляем изменения

    `git add <. or file-name>`

4. Повторяем 2 пункт
5. Сохраняем изменения

    `git commit -m "commit-message"`

6. Поторяем пункт 2
7. Отправить изменения в гит вместе с веткой

    `git push origin <branch-name>`

## После выполнения работы

1. Отправить изменения в гит вместе с веткой

    `git push origin <branch-name>`

2. Идём в гит и делаем пулреквест