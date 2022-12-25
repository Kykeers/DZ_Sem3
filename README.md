* Семинар №3 DZ

# Клонирование репозитория

git clone git@github.com:nicothin/web-design.git # клонировать удаленный репозиторий в одноименную папку
git clone git@github.com:nicothin/web-design.git foldername # клонировать удаленный репозиторий в папку «foldername»
git clone git@github.com:nicothin/web-design.git . # клонировать репозиторий в текущую папку

# Удалённые репозитории

git remote -v # показать список удалённых репозиториев, связанных с этим
git remote remove origin # убрать привязку удалённого репозитория с сокр. именем origin
git remote add origin git@github.com:nicothin/test.git # добавить удалённый репозиторий (с сокр. именем origin) с указанным URL
git remote rm origin # удалить привязку удалённого репозитория
git remote show origin # получить данные об удалённом репозитории с сокращенным именем origin
git fetch origin # скачать все ветки с удаленного репозитория (с сокр. именем origin), но не сливать со своими ветками
git fetch origin master # то же, но скачивается только указанная ветка
git checkout origin/github_branch # посмотреть ветку, скачанную с удалённого репозитория (локальной редактируемой копии не создаётся! если нужно редактировать, придётся влить)
git checkout --track origin/github_branch # создать локальную ветку github_branch (данные взять из удалённого репозитория с сокр. именем origin, ветка github_branch) и переключиться на неё
git push origin master # отправить в удалённый репозиторий (с сокр. именем origin) данные своей ветки master
git pull origin # влить изменения с удалённого репозитория (все ветки)
git pull origin master # влить изменения с удалённого репозитория (только указанная ветка)

# Начало работы

# указана последовательность действий:
git init # инициируем гит в этой папке
touch readme.md # создаем файл readme.md
git add readme.md # делаем этот файл отслеживаемым
git commit -m "Первый коммит" # создаем первый коммит с вменяемым названием
git remote add origin git@github.com:nicothin/test.git # добавляем предварительно созданный пустой удаленный репозиторий
git push origin master # отправляем данные из локального репозитория в удаленный (в ветку master)
 
25.12.2022