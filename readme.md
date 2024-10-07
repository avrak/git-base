* `git init` - инициализировать локальный репозиторий git
* `git status` - показать статус репозитория
* `rm -rf .git` - "разгитить" папку
* `git add [key]|[file_name]` - добавить файл в папке к репозиторию  ключи:
    * `all` - все файлы в данной папке
    * `.` - всю текущую папку
* `git commit -m "<Описание>"` - зафиксировать изменения в репозитории
* `git log` - история изменений репозитория
* `git push -u origin master` - пуш в мастер
* `git remote add origin https://github.com/YandexPracticum/first-project.git` — привяжи локальный репозиторий к удалённому с URL https://github.com/YandexPracticum/first-project.git;
* `git remote -v` (от англ. verbose, «подробный») — проверь, что репозитории действительно связались;
* `git push -u origin main` (от англ. push, «толкать») — в первый раз загрузи все коммиты из локального репозитория в удалённый с названием origin.