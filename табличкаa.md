# Полная таблица Git команд

| № | Команда | Описание | Основные ключи | Пример | Скриншот выполнения |
|---|---------|----------|----------------|--------|---------------------|
| 1 | `git init` | Создать новый репозиторий | `--bare`, `-q` | `git init проект` | ![alt text](image.png)** |
| 2 | `git clone` | Клонировать репозиторий | `--depth`, `--branch` | `git clone https://github.com/...` | ![alt text](image-1.png)** |
| 3 | `git add` | Добавить файлы в staging | `.`, `-p`, `-A` | `git add .` | ![alt text](image-2.png)** |
| 4 | `git commit` | Сделать коммит | `-m`, `-a`, `--amend` | `git commit -m "сообщение"` | ![alt text](image-3.png)** |
| 5 | `git status` | Показать статус | `-s`, `-b` | `git status -s` | ![alt text](image-4.png)** |
| 6 | `git push` | Отправить на сервер | `-u`, `--force` | `git push origin main` | ![alt text](image-5.png)** |
| 7 | `git pull` | Получить с сервера | `--rebase` | `git pull origin main` | ![alt text](image-6.png)** |
| 8 | `git fetch` | Загрузить изменения | `--all` | `git fetch --all` | ![alt text](image-7.png)** |
| 9 | `git branch` | Работа с ветками | `-a`, `-d`, `-m` | `git branch -a` | ![alt text](image-8.png)** |
| 10 | `git checkout` | Переключить ветку | `-b` | `git checkout -b новая` | ![alt text](image-9.png)** |
| 11 | `git merge` | Слить ветки | `--no-ff`, `--abort` | `git merge feature` | ![alt text](image-10.png)** |
| 12 | `git diff` | Показать различия | `--staged` | `git diff HEAD~1` | ![alt text](image-11.png)** |
| 13 | `git log` | История коммитов | `--oneline`, `--graph` | `git log --oneline` | ![alt text](image-12.png)** |
| 14 | `git reset` | Отменить коммит | `--soft`, `--hard` | `git reset --soft HEAD~1` | ![alt text](image-13.png)** |
| 15 | `git revert` | Отменить изменения | | `git revert abc123` | ![alt text](image-14.png)** |
| 16 | `git stash` | Временно сохранить | `save`, `pop` | `git stash save "работа"` | ![alt text](image-15.png)** |
| 17 | `git tag` | Работа с тегами | `-a` | `git tag v1.0` | ![alt text](image-16.png)** |
| 18 | `git remote` | Удаленные репозитории | `add`, `-v` | `git remote add origin url` | ![alt text](image-1.png)** |
| 19 | `git show` | Показать коммит | `--stat` | `git show abc123` | ![alt text](image.png)** |
| 20 | `git rm` | Удалить файл | `--cached` | `git rm file.txt` | ![alt text](image-19.png)** |
| 21 | `git mv` | Переместить файл | | `git mv old new` | ![alt text](image-20.png)** |
| 22 | `git clean` | Очистить проект | `-fd` | `git clean -fd` | ![alt text](image-21.png)** |
| 23 | `git grep` | Поиск в коде | `-n` | `git grep "TODO"` | ![alt text](image-22.png)** |
| 24 | `git rebase` | Перебазировать | `-i` | `git rebase -i HEAD~3` | ![alt text](image-23.png)** |
| 25 | `git cherry-pick` | Взять коммит | `-n` | `git cherry-pick abc123` | ![alt text](image-24.png)** |
| 26 | `git bisect` | Найти баг | `start`, `bad`, `good` | `git bisect start` | ![alt text](image-25.png)** |
| 27 | `git blame` | Автор строк | `-L` | `git blame file.txt -L 10,20` | ![alt text](image-26.png)** |
| 28 | `git config` | Настройки | `--global` | `git config user.name "Имя"` | ![alt text](image.png)** |
| 29 | `git help` | Помощь | | `git help commit` | ![alt text](image-28.png)** |
| 30 | `git archive` | Создать архив | `--format=zip` | `git archive -o release.zip HEAD` | ![alt text](image-29.png)** |
| 31 | `git describe` | Описать коммит | `--tags` | `git describe --tags` | ![alt text](image-10.png)** |
| 32 | `git shortlog` | Сводка по авторам | `-sn` | `git shortlog -sn` | ![alt text](image-12.png)** |
| 33 | `git whatchanged` | Что изменилось | `-p` | `git whatchanged --since="1 week"` | ![alt text](image-14.png)** |
| 34 | `git reflog` | История HEAD | `show` | `git reflog show` | ![alt text](image-33.png)** |
| 35 | `git gc` | Сборка мусора | `--auto` | `git gc --auto` | ![alt text](image-34.png)** |
| 36 | `git fsck` | Проверить целостность | `--full` | `git fsck --full` | ![alt text](image-35.png)** |
| 37 | `git prune` | Удалить лишнее | `--expire` | `git prune --expire=now` | ![alt text](image-36.png)** |
| 38 | `git count-objects` | Подсчет объектов | `-v` | `git count-objects -v` | ![alt text](image-37.png)** |
| 39 | `git verify-pack` | Проверить pack | `-v` | `git verify-pack -v .git/objects/pack/*.idx` | ![alt text](image-38.png)** |
| 40 | `git cat-file` | Инфо об объекте | `-t`, `-p` | `git cat-file -p HEAD` | ![alt text](image-39.png)** |
| 41 | `git update-index` | Обновить индекс | `--assume-unchanged` | `git update-index --assume-unchanged file` | ![alt text](image-40.png)** |
| 42 | `git write-tree` | Записать дерево | | `git write-tree` | ![alt text](image.png)** |
| 43 | `git commit-tree` | Коммит из дерева | `-p` | `git commit-tree abc -m "msg"` | ![alt text](image-71.png)** |
| 44 | `git mktree` | Создать дерево | `-z` | `echo "100644 blob abc file" | git mktree` | ![alt text](image-50.png)** |
| 45 | `git mktag` | Создать тег | `--strict` | `git mke abc123` | ![alt text](image-75.png)** |
| 47 | `git diff-index` | Сравнить с индексом | `--cached` | `gtag < tag-file` | ![alt text](image-69.png)** |
| 46 | `git unpack-file` | Распаковать файл | | `git unpack-filit diff-index HEAD` | ![alt text](image-5.png)** |
| 48 | `git update-ref` | Обновить ссылку | `-d` | `git update-ref refs/heads/new abc123` | ![alt text](image-6.png)** |
| 49 | `git symbolic-ref` | Символическая ссылка | `-q` | `git symbolic-ref HEAD` | ![alt text](image-7.png)** |
| 50 | `git check-ignore` | Проверить игнор | `-v` | `git check-ignore -v file` | ![alt text](image-74.png)** |
| 51 | `git check-mailmap` | Проверить mailmap | `--stdin` | `echo "Name" | git check-mailmap` | ![alt text](image-73.png)** |
| 52 | `git check-ref-format` | Проверить имя ссылки | `--branch` | `git check-ref-format --branch "name"` | ![alt text](image-72.png)** |
| 53 | `git column` | Форматировать в колонки | `--mode=column` | `git branch | git column --mode=column` | ![alt text](image-76.png)** |
| 54 | `git credential-cache` | Кэш учетных данных | `--timeout` | `git credential-cache --timeout=3600` | ![alt text](image-12.png)** |
| 55 | `git credential-store` | Хранилище учетных данных | `--file` | `git credential-store --file=~/.git-credentials` | ![alt text](image-13.png)** |
| 56 | `git fmt-merge-msg` | Формат сообщения слияния | `--log` | `git fmt-merge-msg < .git/MERGE_MSG` | ![alt text](image-14.png)** |
| 57 | `git interpret-trailers` | Управление трейлерами | `--trailer` | `git interpret-trailers --trailer="Signed-off-by: Name"` | ![alt text](image-15.png)** |
| 58 | `git mailinfo` | Инфо из email | `-k` | `git mailinfo msg diff` | ![alt text](image-16.png)** |
| 59 | `git mailsplit` | Разделить mbox | `-o` | `git mailsplit -o patches < mailbox` | ![alt text](image-17.png)** |
| 60 | `git merge-file` | Слить три файла | `-p` | `git merge-file current base other` | ![alt text](image-18.png)** |
| 61 | `git merge-index` | Слияние по индексу | `-o` | `git merge-index -o git-merge-one-file` | ![alt text](image-19.png)** |
| 62 | `git merge-one-file` | Слить один файл | | `git merge-one-file base current other` | ![alt text](image-20.png)** |
| 63 | `git patch-id` | ID патча | `--stable` | `git patch-id < patch.diff` | ![alt text](image-21.png)** |
| 64 | `git rerere` | Повторное разрешение | `clear` | `git rerere clear` | ![alt text](image-22.png)** |
| 65 | `git rev-list` | Список коммитов | `--all` | `git rev-list --all --since="2023-01-01"` | ![alt text](image-23.png)** |
| 66 | `git rev-parse` | Разобрать параметры | `--git-dir` | `git rev-parse --show-toplevel` | ![alt text](image-24.png)** |
| 67 | `git stripspace` | Убрать пробелы | `-s` | `echo "  text  " | git stripspace` | ![alt text](image-25.png)** |
| 68 | `git var` | Показать переменные | `-l` | `git var GIT_AUTHOR_IDENT` | ![alt text](image-26.png)** |
| 69 | `git web--browse` | Открыть в браузере | `-b` | `git web--browse https://github.com` | ![alt text](image-27.png)** |
| 70 | `git apply` | Применить патч | `--stat` | `git apply patch.diff` | ![alt text](image-28.png)** |
| 71 | `git checkout-index` | Скопировать из индекса | `-a` | `git checkout-index -a` | ![alt text](image-29.png)** |
| 72 | `git commit-graph` | Граф коммитов | `write` | `git commit-graph write --reachable` | ![alt text](image-30.png)** |
| 73 | `git get-tar-commit-id` | ID из tar | | `git get-tar-commit-id < archive.tar` | ![alt text](image-31.png)** |
| 74 | `git gui` | Графический интерфейс | `--version` | `git gui` | ![alt text](image-32.png)** |
| 75 | `git merge-base` | Общий предок | `--all` | `git merge-base main feature` | ![alt text](image-33.png)** |
| 76 | `git name-rev` | Символическое имя | `--tags` | `git name-rev HEAD` | ![alt text](image-34.png)** |
| 77 | `git pack-redundant` | Избыточные packs | `--all` | `git pack-redundant --all` | ![alt text](image-35.png)** |
| 78 | `git range-diff` | Сравнение диапазонов | `--creation-factor` | `git range-diff main..f1 main..f2` | ![alt text](image-36.png)** |
| 79 | `git read-tree` | Чтение дерева в индекс | `-m` | `git read-tree -m HEAD feature` | ![alt text](image-37.png)** |
| 80 | `git sh-i18n` | Интернационализация | `--env` | `git sh-i18n --env` | ![alt text](image-38.png)** |
| 81 | `git show-branch` | Показать ветки | `--all` | `git show-branch --all` | ![alt text](image-39.png)** |
| 82 | `git show-index` | Показать индекс pack | `--object-format` | `git show-index < .git/objects/pack/pack-*.idx` | ![alt text](image-40.png)** |
| 83 | `git show-ref` | Показать ссылки | `--heads` | `git show-ref --heads` | ![alt text](image-41.png)** |
| 84 | `git stage` | Синоним для add | | `git stage file.txt` | ![alt text](image-42.png)** |
| 85 | `git unpack-objects` | Распаковать объекты | `-n` | `git unpack-objects < pack-file.pack` | ![alt text](image-43.png)** |
| 86 | `git update-server-info` | Обновить серверную инфо | `-f` | `git update-server-info` | ![alt text](image-44.png)** |
| 87 | `git upload-archive` | Сервер для archive | `--verbose` | `git upload-archive .` | ![alt text](image-45.png)** |
| 88 | `git upload-pack` | Сервер для fetch | `--stateless-rpc` | `git upload-pack .` | ![alt text](image-46.png)** |
| 89 | `git cvsexportcommit` | Экспорт в CVS | `-c` | `git cvsexportcommit -c -p -v HEAD` | ![alt text](image-1.png)** |
| 90 | `git cvsimport` | Импорт из CVS | `-A` | `git cvsimport -C repo -d :pserver:user@server:/path` | ![alt text](image-2.png)** |
| 91 | `git imap-send` | Отправить по IMAP | `--curl` | `git imap-send --folder=INBOX.Drafts` | ![alt text](image-3.png)** |
| 92 | `git quiltimport` | Импорт quilt | `--patches` | `git quiltimport --patches=patches/*` | ![alt text](image-4.png)** |
| 93 | `git request-pull` | Запрос на pull | `-p` | `git request-pull origin/main feature` | ![alt text](image-5.png)** |
| 94 | `git send-email` | Отправить email | `--to` | `git send-email --to=dev@list.org patch.patch` | ![alt text](image-52.png)** |
| 95 | `git svn` | Работа с SVN | `clone`, `dcommit` | `git svn clone https://svn.example.com/project` | ![alt text](image-53.png)** |
| 96 | `git filter-branch` | Переписать историю | `--tree-filter` | `git filter-branch --tree-filter 'rm -f pass.txt' HEAD` | ![alt text](image-6.png)** |
| 97 | `git replace` | Заменить объект | `--edit` | `git replace bad good` | ![alt text](image-7.png)** |
| 98 | `git credential` | Учетные данные | `fill` | `git credential fill` | ![alt text](image-8.png)** |
| 99 | `git verify-commit` | Проверить подпись коммита | `--verbose` | `git verify-commit HEAD` | ![alt text](image-57.png)** |
| 100 | `git verify-tag` | Проверить подпись тега | `--verbose` | `git verify-tag v1.0` | ![alt text](image-58.png)** |
| 101 | `git worktree` | Несколько рабочих деревьев | `add` | `git worktree add ../hotfix hotfix` | ![alt text](image-59.png)** |
| 102 | `git notes` | Заметки к коммитам | `add` | `git notes add -m "заметка" abc123` | ![alt text](image-9.png)** |
| 103 | `git bundle` | Упаковать в bundle | `create` | `git bundle create repo.bundle HEAD main` | ![alt text](image-61.png)** |
| 104 | `git daemon` | Git демон | `--export-all` | `git daemon --export-all --base-path=/git` | ![alt text](image-10.png)** |
| 105 | `git instaweb` | Веб-интерфейс | `--httpd` | `git instaweb --httpd=webrick --start` | ![alt text](image-11.png)** |
| 106 | `git mergetool` | Инструмент слияния | `--tool` | `git mergetool --tool=vimdiff` | ![alt text](image.png)** |
| 107 | `git difftool` | Инструмент сравнения | `--tool` | `git difftool --tool=meld HEAD~1` | ![alt text](image-1.png)** |
| 108 | `git submodule` | Подмодули | `add`, `update` | `git submodule add https://github.com/user/sub.git` | ![alt text](image-2.png)** |
| 109 | `git switch` | Новый способ переключения | `-c` | `git switch -c новая-ветка` | ![alt text](image-3.png)** |
| 110 | `git restore` | Новый способ восстановления | `--staged` | `git restore --staged file.txt` | ![alt text](image-4.png)** |

## 📊 Статистика по категориям
- **Основные команды:** 30 команд (используются ежедневно)
- **Продвинутые команды:** 40 команд (используются периодически)
- **Специализированные:** 40 команд (для специфических задач)