\# Полная таблица Git команд (110 команд)



| № | Команда | Описание | Основные ключи | Пример | Скриншот |

|---|---|---|---|---|---|

| 1 | `git init` | Создать новый репозиторий | `--bare`, `-q` | `git init проект` | !\[](https://via.placeholder.com/100x50/008000/FFFFFF?text=init) |

| 2 | `git clone` | Клонировать репозиторий | `--depth`, `--branch` | `git clone https://github.com/...` | !\[](https://via.placeholder.com/100x50/0000FF/FFFFFF?text=clone) |

| 3 | `git add` | Добавить файлы в staging | `.`, `-p`, `-A` | `git add .` | !\[](https://via.placeholder.com/100x50/FFA500/FFFFFF?text=add) |

| 4 | `git commit` | Сделать коммит | `-m`, `-a`, `--amend` | `git commit -m "сообщение"` | !\[](https://via.placeholder.com/100x50/800080/FFFFFF?text=commit) |

| 5 | `git status` | Показать статус | `-s`, `-b` | `git status -s` | !\[](https://via.placeholder.com/100x50/FF0000/FFFFFF?text=status) |

| 6 | `git push` | Отправить на сервер | `-u`, `--force` | `git push origin main` | !\[](https://via.placeholder.com/100x50/FF1493/FFFFFF?text=push) |

| 7 | `git pull` | Получить с сервера | `--rebase` | `git pull origin main` | !\[](https://via.placeholder.com/100x50/4B0082/FFFFFF?text=pull) |

| 8 | `git fetch` | Загрузить изменения | `--all` | `git fetch --all` | !\[](https://via.placeholder.com/100x50/00CED1/FFFFFF?text=fetch) |

| 9 | `git branch` | Работа с ветками | `-a`, `-d`, `-m` | `git branch -a` | !\[](https://via.placeholder.com/100x50/32CD32/FFFFFF?text=branch) |

| 10 | `git checkout` | Переключить ветку | `-b` | `git checkout -b новая` | !\[](https://via.placeholder.com/100x50/DC143C/FFFFFF?text=checkout) |

| 11 | `git merge` | Слить ветки | `--no-ff`, `--abort` | `git merge feature` | !\[](https://via.placeholder.com/100x50/8A2BE2/FFFFFF?text=merge) |

| 12 | `git diff` | Показать различия | `--staged` | `git diff HEAD~1` | !\[](https://via.placeholder.com/100x50/FF69B4/FFFFFF?text=diff) |

| 13 | `git log` | История коммитов | `--oneline`, `--graph` | `git log --oneline` | !\[](https://via.placeholder.com/100x50/00FA9A/FFFFFF?text=log) |

| 14 | `git reset` | Отменить коммит | `--soft`, `--hard` | `git reset --soft HEAD~1` | !\[](https://via.placeholder.com/100x50/1E90FF/FFFFFF?text=reset) |

| 15 | `git revert` | Отменить изменения | | `git revert abc123` | !\[](https://via.placeholder.com/100x50/FF4500/FFFFFF?text=revert) |

| 16 | `git stash` | Временно сохранить | `save`, `pop` | `git stash save "работа"` | !\[](https://via.placeholder.com/100x50/9400D3/FFFFFF?text=stash) |

| 17 | `git tag` | Работа с тегами | `-a` | `git tag v1.0` | !\[](https://via.placeholder.com/100x50/8B0000/FFFFFF?text=tag) |

| 18 | `git remote` | Удаленные репозитории | `add`, `-v` | `git remote add origin url` | !\[](https://via.placeholder.com/100x50/556B2F/FFFFFF?text=remote) |

| 19 | `git show` | Показать коммит | `--stat` | `git show abc123` | !\[](https://via.placeholder.com/100x50/FF8C00/FFFFFF?text=show) |

| 20 | `git rm` | Удалить файл | `--cached` | `git rm file.txt` | !\[](https://via.placeholder.com/100x50/9932CC/FFFFFF?text=rm) |

| 21 | `git mv` | Переместить файл | | `git mv old new` | !\[](https://via.placeholder.com/100x50/4682B4/FFFFFF?text=mv) |

| 22 | `git clean` | Очистить проект | `-fd` | `git clean -fd` | !\[](https://via.placeholder.com/100x50/8B4513/FFFFFF?text=clean) |

| 23 | `git grep` | Поиск в коде | `-n` | `git grep "TODO"` | !\[](https://via.placeholder.com/100x50/2E8B57/FFFFFF?text=grep) |

| 24 | `git rebase` | Перебазировать | `-i` | `git rebase -i HEAD~3` | !\[](https://via.placeholder.com/100x50/9400D3/FFFFFF?text=rebase) |

| 25 | `git cherry-pick` | Взять коммит | `-n` | `git cherry-pick abc123` | !\[](https://via.placeholder.com/100x50/8B008B/FFFFFF?text=cherry) |

| 26 | `git bisect` | Найти баг | `start`, `bad`, `good` | `git bisect start` | !\[](https://via.placeholder.com/100x50/FF6347/FFFFFF?text=bisect) |

| 27 | `git blame` | Автор строк | `-L` | `git blame file.txt -L 10,20` | !\[](https://via.placeholder.com/100x50/6A5ACD/FFFFFF?text=blame) |

| 28 | `git config` | Настройки | `--global` | `git config user.name "Имя"` | !\[](https://via.placeholder.com/100x50/228B22/FFFFFF?text=config) |

| 29 | `git help` | Помощь | | `git help commit` | !\[](https://via.placeholder.com/100x50/20B2AA/FFFFFF?text=help) |

| 30 | `git archive` | Создать архив | `--format=zip` | `git archive -o release.zip HEAD` | !\[](https://via.placeholder.com/100x50/BC8F8F/FFFFFF?text=archive) |

| 31 | `git describe` | Описать коммит | `--tags` | `git describe --tags` | !\[](https://via.placeholder.com/100x50/483D8B/FFFFFF?text=describe) |

| 32 | `git shortlog` | Сводка по авторам | `-sn` | `git shortlog -sn` | !\[](https://via.placeholder.com/100x50/2F4F4F/FFFFFF?text=shortlog) |

| 33 | `git whatchanged` | Что изменилось | `-p` | `git whatchanged --since="1 week"` | !\[](https://via.placeholder.com/100x50/800000/FFFFFF?text=whatchanged) |

| 34 | `git reflog` | История HEAD | `show` | `git reflog show` | !\[](https://via.placeholder.com/100x50/8B0000/FFFFFF?text=reflog) |

| 35 | `git gc` | Сборка мусора | `--auto` | `git gc --auto` | !\[](https://via.placeholder.com/100x50/556B2F/FFFFFF?text=gc) |

| 36 | `git fsck` | Проверить целостность | `--full` | `git fsck --full` | !\[](https://via.placeholder.com/100x50/9932CC/FFFFFF?text=fsck) |

| 37 | `git prune` | Удалить лишнее | `--expire` | `git prune --expire=now` | !\[](https://via.placeholder.com/100x50/8FBC8F/FFFFFF?text=prune) |

| 38 | `git count-objects` | Подсчет объектов | `-v` | `git count-objects -v` | !\[](https://via.placeholder.com/100x50/483D8B/FFFFFF?text=count) |

| 39 | `git verify-pack` | Проверить pack | `-v` | `git verify-pack -v .git/objects/pack/\*.idx` | !\[](https://via.placeholder.com/100x50/2E8B57/FFFFFF?text=verify) |

| 40 | `git cat-file` | Инфо об объекте | `-t`, `-p` | `git cat-file -p HEAD` | !\[](https://via.placeholder.com/100x50/8B4513/FFFFFF?text=cat-file) |

| 41 | `git update-index` | Обновить индекс | `--assume-unchanged` | `git update-index --assume-unchanged file` | !\[](https://via.placeholder.com/100x50/4682B4/FFFFFF?text=update-index) |

| 42 | `git write-tree` | Записать дерево | | `git write-tree` | !\[](https://via.placeholder.com/100x50/9400D3/FFFFFF?text=write-tree) |

| 43 | `git commit-tree` | Коммит из дерева | `-p` | `git commit-tree abc -m "msg"` | !\[](https://via.placeholder.com/100x50/FF1493/FFFFFF?text=commit-tree) |

| 44 | `git mktree` | Создать дерево | `-z` | `echo "100644 blob abc file" | git mktree` | !\[](https://via.placeholder.com/100x50/00CED1/FFFFFF?text=mktree) |

| 45 | `git mktag` | Создать тег | `--strict` | `git mktag < tag-file` | !\[](https://via.placeholder.com/100x50/8A2BE2/FFFFFF?text=mktag) |

| 46 | `git unpack-file` | Распаковать файл | | `git unpack-file blob-hash` | !\[](https://via.placeholder.com/100x50/DC143C/FFFFFF?text=unpack) |

| 47 | `git diff-index` | Сравнить с индексом | `--cached` | `git diff-index HEAD` | !\[](https://via.placeholder.com/100x50/32CD32/FFFFFF?text=diff-index) |

| 48 | `git update-ref` | Обновить ссылку | `-d` | `git update-ref refs/heads/new abc123` | !\[](https://via.placeholder.com/100x50/FF8C00/FFFFFF?text=update-ref) |

| 49 | `git symbolic-ref` | Символическая ссылка | `-q` | `git symbolic-ref HEAD` | !\[](https://via.placeholder.com/100x50/9932CC/FFFFFF?text=symbolic) |

| 50 | `git check-ignore` | Проверить игнор | `-v` | `git check-ignore -v file` | !\[](https://via.placeholder.com/100x50/8B0000/FFFFFF?text=check-ignore) |

| 51 | `git check-mailmap` | Проверить mailmap | `--stdin` | `echo "Name" | git check-mailmap` | !\[](https://via.placeholder.com/100x50/556B2F/FFFFFF?text=mailmap) |

| 52 | `git check-ref-format` | Проверить имя ссылки | `--branch` | `git check-ref-format --branch "name"` | !\[](https://via.placeholder.com/100x50/2F4F4F/FFFFFF?text=check-ref) |

| 53 | `git column` | Форматировать в колонки | `--mode=column` | `git branch | git column --mode=column` | !\[](https://via.placeholder.com/100x50/800080/FFFFFF?text=column) |

| 54 | `git credential-cache` | Кэш учетных данных | `--timeout` | `git credential-cache --timeout=3600` | !\[](https://via.placeholder.com/100x50/FF4500/FFFFFF?text=cred-cache) |

| 55 | `git credential-store` | Хранилище учетных данных | `--file` | `git credential-store --file=~/.git-credentials` | !\[](https://via.placeholder.com/100x50/8B4513/FFFFFF?text=cred-store) |

| 56 | `git fmt-merge-msg` | Формат сообщения слияния | `--log` | `git fmt-merge-msg < .git/MERGE\_MSG` | !\[](https://via.placeholder.com/100x50/2E8B57/FFFFFF?text=fmt-merge) |

| 57 | `git interpret-trailers` | Управление трейлерами | `--trailer` | `git interpret-trailers --trailer="Signed-off-by: Name"` | !\[](https://via.placeholder.com/100x50/9400D3/FFFFFF?text=trailers) |

| 58 | `git mailinfo` | Инфо из email | `-k` | `git mailinfo msg diff` | !\[](https://via.placeholder.com/100x50/8B008B/FFFFFF?text=mailinfo) |

| 59 | `git mailsplit` | Разделить mbox | `-o` | `git mailsplit -o patches < mailbox` | !\[](https://via.placeholder.com/100x50/FF6347/FFFFFF?text=mailsplit) |

| 60 | `git merge-file` | Слить три файла | `-p` | `git merge-file current base other` | !\[](https://via.placeholder.com/100x50/6A5ACD/FFFFFF?text=merge-file) |

| 61 | `git merge-index` | Слияние по индексу | `-o` | `git merge-index -o git-merge-one-file` | !\[](https://via.placeholder.com/100x50/228B22/FFFFFF?text=merge-index) |

| 62 | `git merge-one-file` | Слить один файл | | `git merge-one-file base current other` | !\[](https://via.placeholder.com/100x50/20B2AA/FFFFFF?text=merge-one) |

| 63 | `git patch-id` | ID патча | `--stable` | `git patch-id < patch.diff` | !\[](https://via.placeholder.com/100x50/BC8F8F/FFFFFF?text=patch-id) |

| 64 | `git rerere` | Повторное разрешение | `clear` | `git rerere clear` | !\[](https://via.placeholder.com/100x50/483D8B/FFFFFF?text=rerere) |

| 65 | `git rev-list` | Список коммитов | `--all` | `git rev-list --all --since="2023-01-01"` | !\[](https://via.placeholder.com/100x50/2F4F4F/FFFFFF?text=rev-list) |

| 66 | `git rev-parse` | Разобрать параметры | `--git-dir` | `git rev-parse --show-toplevel` | !\[](https://via.placeholder.com/100x50/800000/FFFFFF?text=rev-parse) |

| 67 | `git stripspace` | Убрать пробелы | `-s` | `echo "  text  " | git stripspace` | !\[](https://via.placeholder.com/100x50/8B0000/FFFFFF?text=stripspace) |

| 68 | `git var` | Показать переменные | `-l` | `git var GIT\_AUTHOR\_IDENT` | !\[](https://via.placeholder.com/100x50/556B2F/FFFFFF?text=var) |

| 69 | `git web--browse` | Открыть в браузере | `-b` | `git web--browse https://github.com` | !\[](https://via.placeholder.com/100x50/9932CC/FFFFFF?text=web) |

| 70 | `git apply` | Применить патч | `--stat` | `git apply patch.diff` | !\[](https://via.placeholder.com/100x50/8FBC8F/FFFFFF?text=apply) |

| 71 | `git checkout-index` | Скопировать из индекса | `-a` | `git checkout-index -a` | !\[](https://via.placeholder.com/100x50/483D8B/FFFFFF?text=checkout-idx) |

| 72 | `git commit-graph` | Граф коммитов | `write` | `git commit-graph write --reachable` | !\[](https://via.placeholder.com/100x50/2E8B57/FFFFFF?text=commit-graph) |

| 73 | `git get-tar-commit-id` | ID из tar | | `git get-tar-commit-id < archive.tar` | !\[](https://via.placeholder.com/100x50/8B4513/FFFFFF?text=tar-id) |

| 74 | `git gui` | Графический интерфейс | `--version` | `git gui` | !\[](https://via.placeholder.com/100x50/4682B4/FFFFFF?text=gui) |

| 75 | `git merge-base` | Общий предок | `--all` | `git merge-base main feature` | !\[](https://via.placeholder.com/100x50/9400D3/FFFFFF?text=merge-base) |

| 76 | `git name-rev` | Символическое имя | `--tags` | `git name-rev HEAD` | !\[](https://via.placeholder.com/100x50/FF1493/FFFFFF?text=name-rev) |

| 77 | `git pack-redundant` | Избыточные packs | `--all` | `git pack-redundant --all` | !\[](https://via.placeholder.com/100x50/00CED1/FFFFFF?text=pack-red) |

| 78 | `git range-diff` | Сравнение диапазонов | `--creation-factor` | `git range-diff main..f1 main..f2` | !\[](https://via.placeholder.com/100x50/8A2BE2/FFFFFF?text=range-diff) |

| 79 | `git read-tree` | Чтение дерева в индекс | `-m` | `git read-tree -m HEAD feature` | !\[](https://via.placeholder.com/100x50/DC143C/FFFFFF?text=read-tree) |

| 80 | `git sh-i18n` | Интернационализация | `--env` | `git sh-i18n --env` | !\[](https://via.placeholder.com/100x50/32CD32/FFFFFF?text=i18n) |

| 81 | `git show-branch` | Показать ветки | `--all` | `git show-branch --all` | !\[](https://via.placeholder.com/100x50/FF8C00/FFFFFF?text=show-branch) |

| 82 | `git show-index` | Показать индекс pack | `--object-format` | `git show-index < .git/objects/pack/pack-\*.idx` | !\[](https://via.placeholder.com/100x50/9932CC/FFFFFF?text=show-index) |

| 83 | `git show-ref` | Показать ссылки | `--heads` | `git show-ref --heads` | !\[](https://via.placeholder.com/100x50/8B0000/FFFFFF?text=show-ref) |

| 84 | `git stage` | Синоним для add | | `git stage file.txt` | !\[](https://via.placeholder.com/100x50/556B2F/FFFFFF?text=stage) |

| 85 | `git unpack-objects` | Распаковать объекты | `-n` | `git unpack-objects < pack-file.pack` | !\[](https://via.placeholder.com/100x50/2F4F4F/FFFFFF?text=unpack-obj) |

| 86 | `git update-server-info` | Обновить серверную инфо | `-f` | `git update-server-info` | !\[](https://via.placeholder.com/100x50/800080/FFFFFF?text=server-info) |

| 87 | `git upload-archive` | Сервер для archive | `--verbose` | `git upload-archive .` | !\[](https://via.placeholder.com/100x50/FF4500/FFFFFF?text=upload-arch) |

| 88 | `git upload-pack` | Сервер для fetch | `--stateless-rpc` | `git upload-pack .` | !\[](https://via.placeholder.com/100x50/8B4513/FFFFFF?text=upload-pack) |

| 89 | `git cvsexportcommit` | Экспорт в CVS | `-c` | `git cvsexportcommit -c -p -v HEAD` | !\[](https://via.placeholder.com/100x50/2E8B57/FFFFFF?text=cvsexport) |

| 90 | `git cvsimport` | Импорт из CVS | `-A` | `git cvsimport -C repo -d :pserver:user@server:/path` | !\[](https://via.placeholder.com/100x50/9400D3/FFFFFF?text=cvsimport) |

| 91 | `git imap-send` | Отправить по IMAP | `--curl` | `git imap-send --folder=INBOX.Drafts` | !\[](https://via.placeholder.com/100x50/8B008B/FFFFFF?text=imap) |

| 92 | `git quiltimport` | Импорт quilt | `--patches` | `git quiltimport --patches=patches/\*` | !\[](https://via.placeholder.com/100x50/FF6347/FFFFFF?text=quilt) |

| 93 | `git request-pull` | Запрос на pull | `-p` | `git request-pull origin/main feature` | !\[](https://via.placeholder.com/100x50/6A5ACD/FFFFFF?text=request) |

| 94 | `git send-email` | Отправить email | `--to` | `git send-email --to=dev@list.org patch.patch` | !\[](https://via.placeholder.com/100x50/228B22/FFFFFF?text=send-email) |

| 95 | `git svn` | Работа с SVN | `clone`, `dcommit` | `git svn clone https://svn.example.com/project` | !\[](https://via.placeholder.com/100x50/20B2AA/FFFFFF?text=svn) |

| 96 | `git filter-branch` | Переписать историю | `--tree-filter` | `git filter-branch --tree-filter 'rm -f pass.txt' HEAD` | !\[](https://via.placeholder.com/100x50/BC8F8F/FFFFFF?text=filter) |

| 97 | `git replace` | Заменить объект | `--edit` | `git replace bad good` | !\[](https://via.placeholder.com/100x50/483D8B/FFFFFF?text=replace) |

| 98 | `git credential` | Учетные данные | `fill` | `git credential fill` | !\[](https://via.placeholder.com/100x50/2F4F4F/FFFFFF?text=credential) |

| 99 | `git verify-commit` | Проверить подпись коммита | `--verbose` | `git verify-commit HEAD` | !\[](https://via.placeholder.com/100x50/800000/FFFFFF?text=verify-commit) |

| 100 | `git verify-tag` | Проверить подпись тега | `--verbose` | `git verify-tag v1.0` | !\[](https://via.placeholder.com/100x50/8B0000/FFFFFF?text=verify-tag) |

| 101 | `git worktree` | Несколько рабочих деревьев | `add` | `git worktree add ../hotfix hotfix` | !\[](https://via.placeholder.com/100x50/556B2F/FFFFFF?text=worktree) |

| 102 | `git notes` | Заметки к коммитам | `add` | `git notes add -m "заметка" abc123` | !\[](https://via.placeholder.com/100x50/9932CC/FFFFFF?text=notes) |

| 103 | `git bundle` | Упаковать в bundle | `create` | `git bundle create repo.bundle HEAD main` | !\[](https://via.placeholder.com/100x50/8FBC8F/FFFFFF?text=bundle) |

| 104 | `git daemon` | Git демон | `--export-all` | `git daemon --export-all --base-path=/git` | !\[](https://via.placeholder.com/100x50/483D8B/FFFFFF?text=daemon) |

| 105 | `git instaweb` | Веб-интерфейс | `--httpd` | `git instaweb --httpd=webrick --start` | !\[](https://via.placeholder.com/100x50/2E8B57/FFFFFF?text=instaweb) |

| 106 | `git mergetool` | Инструмент слияния | `--tool` | `git mergetool --tool=vimdiff` | !\[](https://via.placeholder.com/100x50/8B4513/FFFFFF?text=mergetool) |

| 107 | `git difftool` | Инструмент сравнения | `--tool` | `git difftool --tool=meld HEAD~1` | !\[](https://via.placeholder.com/100x50/4682B4/FFFFFF?text=difftool) |

| 108 | `git submodule` | Подмодули | `add`, `update` | `git submodule add https://github.com/user/sub.git` | !\[](https://via.placeholder.com/100x50/9400D3/FFFFFF?text=submodule) |

| 109 | `git switch` | Новый способ переключения | `-c` | `git switch -c новая-ветка` | !\[](https://via.placeholder.com/100x50/FF1493/FFFFFF?text=switch) |

| 110 | `git restore` | Новый способ восстановления | `--staged` | `git restore --staged file.txt` | !\[](https://via.placeholder.com/100x50/00CED1/FFFFFF?text=restore) |



\## Статистика по категориям



| Категория | Количество команд | Примеры |

|---|---|---|

| \*\*Основные команды\*\* | 30 | `git init`, `git commit`, `git push` |

| \*\*Работа с ветками\*\* | 15 | `git branch`, `git merge`, `git checkout` |

| \*\*История и отладка\*\* | 20 | `git log`, `git diff`, `git blame` |

| \*\*Управление файлами\*\* | 10 | `git add`, `git rm`, `git mv` |

| \*\*Работа с удаленными репозиториями\*\* | 8 | `git remote`, `git fetch`, `git pull` |

| \*\*Специальные команды\*\* | 27 | `git filter-branch`, `git submodule`, `git worktree` |



\## Как использовать таблицу



1\. \*\*Для начинающих:\*\* команды 1-20 (базовые операции)

2\. \*\*Для продвинутых:\*\* команды 21-50 (работа с историей)

3\. \*\*Для экспертов:\*\* команды 51-110 (специальные задачи)



> \*\*Примечание:\*\* Замените placeholder изображения на реальные скриншоты команд

