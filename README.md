# GeetHomework

# Инструкция для работы с Git  и удаленными репозиториями

## Что такое Git?
Git - это одна из реализаций распределенных систем контроля версий, имеющая как и локальные, так и удаленные репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория
Для создания репозитория необходимо выполнить команду *git init* в папке с репозиторием в у вас создастся репозиторий (появится скрытая папка .git)

# Создание коммитов

### Git add
Для добавления изменений в коммит используется комманда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется комманда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и вы увидете были ли изменения в файлах или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "Комментарий для коммита(сохранения)"*

## Инструкция для работы с удаленными репозиториями

1. Создали аккаунт на Github
2. Создать локальный репозиторий
3. Подружить ваш локальный и удаленный репозиторий
4. Отправить ваш локальный репозиторий в удаленный
5. Провести изменения "c другого компьютера"
6. Выкачать (pull) актуальное состояние из удаленного репозитория