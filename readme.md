# Шпаргалка markdown

## Выделение текста

Вы можете выделять текст в markdown с помощью символов `_` или `*`. Например:

Пример _курсива_ и **жирного** текста.

## Заголовки

Заголовки можно создавать с помощью символа `#`. Чем больше `#`, тем меньше заголовок. Например:

# Заголовок первого уровня

## Заголовок второго уровня

### Заголовок третьего уровня

## Выделение кода

Чтобы выделить текст как код, поместите его в тройные кавычки `````.

```
mkdir my_project
cd my_project
git init
```

Это лишь некоторые функции markdown.

## Хеш

Когда будет `commit` у нас появится хеш
**Хеш нужен для того чобы отслеживать**.

Хеш из разных компов но один иизменения дает один и тот же хеш но хеш всегда будет уникальными

## LOG

`git.log` нужен что посмотреть все коммиты

там будет

```
1) commit и хеш
Author
Date

    файл для изменеие
```

commit-ы отсортирован по убвыанию (первый commit это последний commit изменения).

есть кратки варианты `git log --oneline`

## HEAD - заголовок

HEAD - это самый последний хеш данный для commit 
в папке .git/ есть файл HEAD там хранится путь к файлу где хранится последний хеш данный commit-a