# Инструкция по работе с Git

## Подготовка репозитория
Для создания репозитория используется команда *git init*. Чтобы созадать репозиторий напишите в терминале с открытой папкой для репозитория *git init*.

## Добавление файлов в репозиторий

Для добавления файла к коммиту используется комманда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*.

## Создание коммита
Для создания коммита используется команда *git commit*. Чтобы создать новый коммит в терминале с открытой папкой-репозиторием пишем команду *git commit -m "<сообщение к коммиту>"*. Сообщения к коммитам писать ***ОБЯЗАТЕЛЬНО***.

## Текущее состояние Git

Команда git status показывает текущее состояние гита, есть ли изменения, которые нужно сохранить. Для этого в терминале с папкой-репозиторием необходимо написать *git status*.

## Журнал изменений

Чтобы увидеть количество сохранений и сообщений необходимо использовать команду *git log*. Для этого в терминале с папкой-репозиторием необходимо написать *git log*.

## Переключение между версиями

Для переключения между версиями (ветками, комментариями) необходимо использовать команду *git checkout*. Например для перехода к основной ветке необходимо набрать команду git checkout master.

## Команда git diff

Для того,чтобы увидеть разницу между текущим и сохраненным файлом необходимо вызвать команду *git diff*. Для этого в терминале с папкой-репозиторием необходимо написать *git diff*.

## Работа с ветками

Для того, чтобы создать новую ветку необходимо воспользоваться командой *git branch  "имя новой ветки"*. Чтобы посмотреть все ветки которые есть в репозитории необходимо вызвать команду *git branch*.

## Удаление веток

После слияния ветки с основной, ее необходимо удалить. Для того,чтобы это сделать необходимо написать команду *git branch -d <имя ветки которую хотите удалить>*.

## Визуализация всех веток

Параметр,который позвоняет видеть историю в виде дерева, называется graph. Для этого в терминале с папкой-репозиторием необходимо написать *git log --graph*.