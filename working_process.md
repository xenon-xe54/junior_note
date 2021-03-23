# Git-памятка

## Сборник команд

1. Клон репо из своего гита
  
    `git clone ssh-key-repo`
2. Переход в репо
  
    `cd name-folder`
3. Создание новой ветки с переходом на неё
  
    `git checkout -b name-branch`
4. Проверяем ветки
  
    `git branch`
5. Проверяем ремоуты
  
    `git remote -v`
6. Добавляем ремоут
  
    `git remote add name-remote ssh-key-repo-remote`
7. Проверяем изменения
  
    `git status`
8. Добавляем изменения
  
    `git add . or name-file`
9. Сохраняем изменения
  
    `git commit -m "message"`
10. Отправить изменения в гит вместе с веткой
  
    `git push origin name-branch`
11. Переключись на мастер
  
    `git checkout master`
12. Стянуть все изменения из оригинального репо
  
    `git pull parent-repo branch`
13. Обновить форк
  
    `git push origin branch`

## Перед началом работы

1. После всех принятых правок переключись на мастер

    `git checkout master`
2. Стягиваем все изменения из оригинального репо
  
    `git pull parent-repo branch`
3. Обновить форк
  
    `git push origin branch`
4. Создание новой ветки и переключение на неё
  
    `git checkout -b name-branch`
5. Удалить ненужную ветку
  
    `git branch -D name-branch`
6. Обновить форк
  
    `git push origin branch`
7. Проверяем ветки
  
    `git branch`

## При выполнении работы

1. Работаем над проектом
2. Проверяем изменения

    `git status`
3. Добавляем изменения

    `git add . or name-file`
4. Повторяем 2 пункт
5. Сохраняем изменения

    `git commit -m "message"`
6. Поторяем пункт 2

## При поступлении исправлений

1. Работаем над проектом
2. Проверяем изменения

    `git status`
3. Добавляем изменения

    `git add . or name-file`
4. Повторяем 2 пункт
5. Сохраняем изменения

    `git commit -m "message"`
6. Поторяем пункт 2
7. Отправить изменения в гит вместе с веткой

    `git push origin name-branch`

## После выполнения работы

1. Отправить изменения в гит вместе с веткой

    `git push origin name-branch`
2. Идём в гит и делаем пулреквест