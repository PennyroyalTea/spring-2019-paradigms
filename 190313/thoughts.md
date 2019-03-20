https://github.com/progit/progit2-ru
http://gitolite.com/gcs.html

# Техника
## Gitignore, что класть в репозиторий, идеология
Никакого "закомментировали перед отправкой"!

## Working dir, staged, committed
https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D1%8B-Git

## Ветки и тэги
С картинками!

## Remotes: origin, upstream
С картинками!

## Merge conflicts

## Чтение логов
В том числе визуально в IDEA, `git blame`.
## Проверка diff'ов
Должны быть удобные сообщения и diff'ы.
Есть `--color-moved`.
## Выбор версии

## Amend для добавления файла
## Слияние коммитов
## Cherry-pick
## Rebase и переписывание истории
## Разделение коммита
## Reflog

## Просмотр коммитов
`git diff`, `git show`, detached `HEAD`

## CI (Travis)
## Code Coverage

# Конкретные сценарии
## Добавление части изменений в отдельный коммит
Ситуация: наизменяли всякого, убедились, что работает, теперь фиксируем по очереди.
`git add -p`, `git commit`

## Рефакторинг в отдельной ветке как эксперимент
В отдельной ветке поэкспериментировали, в основной ветке
по очереди сделали рефакторинги (несколько коммитов) и
основное изменение (ещё несколько).

## Метод Микадо для рефакторингов

## Синхронизация с origin при наличии конфликтующих изменений
В origin появился важный багфикс и ещё что-то.
`git merge`

## Синхронизация с origin при помощи rebase
`git rebase`

## Чистка истории
`git rebase -i`

# Пример проекта
TODO
## Локальная работа
Нужен проект, в котором есть:
1. Рефакторинг двумя способами (ветки + сравнение)
2. Баг, проявляющийся после рефакторинга (откат, добавление теста, rebase)
3. Баг, проявляющийся просто так (merge conflict при рефакторинге)

## Сдача домашек
Code review, добавление коммитов, удаление лишних коммитов и данных

Как должна выглядеть история

## Работа в команде (теория)