# basic-git-commands
Repository for basic git commands.  
<br>
## git init

- Инициализация пустого репозитория (в текущей папке)
```
git init
```

## git status

- Команда git status показывает состояния файлов в рабочем каталоге и индексе<br>
```
git status
```

## git add

- Команда git add добавляет содержимое рабочего каталога в индекс (staging area) для последующего коммита.<br>
```
git add filename
git add --all
```

## git commit

- Команда git commit берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок.<br>
```
git commit -m "comment about changes"
```

## git log

- Просмотр истории коммитов<br>
```
git log
git log -1  
```

## git push

- Отправка изменений в удалённый репозиторий<br>
```
git push -u origin master // в первый раз, -u для связи локальной ветки с одноимённой удалённой.
git push
```

## Хеш
Хеш — идентификатор коммита  (алгоритм SHA-1)
```
commit 845ecbcce04d6cb5737b2e20ef997abc67e8803f
```

