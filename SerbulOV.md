# Алгоритм начала работы в GIT
1. Создание Git-репозитория: команда **git init**.
2. Проверяем текущее состояние гита, есть 
ли изменения, которые нужно закоммитить
(сохранить) : команда **git status**
3. Добавляем содержимое рабочего каталога , за которым будет следить система: команда **git add**
4. Сохраняем внесенные изменения: **ctrl + S**
5. Фиксируем сохраненные изменения: команда **git commit**
6. Выход на все коммиты : команда **git log**

# Инструкция по работе с удаленными репозиториями

1. Жмем на кнопку Fork (в списке наших репозиториев появился fork)
2. Клонируем к себе в папку: команда **git clone**
3. Открывает папку в VS (проверить место нахождение актуального репозитория: команда **cd**, чтобы поменять имя папки)
4. Выполняем создание новой ветки, в которой будем работать: команда **git branch Имя_ветки**
5. Выполняем переключение на созданную ветку: команда **git checkout Имя_ветки**
6. Добавляем свой файл с названием Имя.MD
7. Выполняем Коммит: команда **git commit -am "имя_фиксации"**
8. выполняем команду: **git push** (если git ругается, выполняем команду из подсказки)
9. на **GITHAB** выполняем **pull request**