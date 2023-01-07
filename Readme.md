# Инструкция по работе с Git

## Что такое гит?
***Git*** - самая популярная реализация распределенной системы контроля версий (версионность поддерживается и на сервере, и у каждого клиента). Самой распространенной реализацией ***Git*** является (GitHub)[https://github.com]

## Подготовка репозиториев
Для создания репозитория используется команда *git init*. Для этого необходимо открыть в терминале папку с будущим репозиторием и написать *git init*.

## Создание коммитов

### Добавление файлов к коммиту
Для добавления файла к новому коммиту используется команда *git add*. Используется она следующим образом: в терминале с папкой-репозиторием пишем *git add <название файла>*.

### Создание коммита
Для создания новой фиксации (коммита) используется команда *git commit*. Для этого в терминале с папкой-репозиторием пишем *git commit -m "<сообщение к коммиту>*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО!!!***.

## Журнал изменений
Для просмотра истории изменений используется команда *git log*. Для этого в терминале с папкой-репозиторием необходимо написать *git log*.

## Перемещение между коммитами
Для перемещения на другую фиксацию (коммит) используется команда *git checkout*. Для этого необходимо, как показано в прошлом пункте, в журнале изменений найти необходимый коммит и его хеш (номер), после чего в терминале с папкой-репозиторием надо написать *git checkout<хеш коммита>*. После выполнения этой команды мы попадаем в состояние **detached head**, в котором никакие следующие коммиты сохранятся не будут. Для выхода из этого состояния необходимо написать *git checkout master*.

## Ветки в гит
Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*
Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*
Для удаления ветки ввести команду "git branch -d 'name branch'"

### Создание ветки
Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток и разрешение конфликтов

## Удаление веток