# Второй Семинар

__Создание веток__
 
команда  *git branch* выводит список всех веток

команда *git branch new_branch* создает новую вестку с нахванием (*new_branch*)

__Слияние веток__

txt

__Конфилкты при слиянии веток__ 

Hello world

# Работа с удаленными репозиториями

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