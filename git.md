---
title: 'Памятка по командам Git'
author: 'А.В. Родионов'
fontsize: '14pt'
geometry: 'margin=2cm'
paper: 'a4'
lang: 'russian'
template: 'default.html'
---

## Просмотр изменений

* `git status` --- просмотр состояния изменений
* `git log` --- история изменений данной ветки
* `git diff` --- сравнение изменений по отношению к текущей ветке
* `git diff` _имя ветки_ --- сравнение изменений по отношению к заданной веткой
* `git diff HEAD~2` --- сравнение изменений по отношению 2, 3 и т.д. коммиту от текущего
* `git diff` _хэш_ ---

git add . --- добавляем изменения
git commit -a -m 'message' --- подтверждение изменений в текущей ветке
git pull --- скачать новые изменения
git push username-project current-branch:remote-branch --- запись текущей ветки в удаленный репозиторий
git reset --hard 'hash code' --- возвращаемся на версию по хеш коду
git branch -a --- отобразить все ветки
git branch -D local-branch --- удалить локальную ветку
git checkout local-branch --- переключится на локальную ветку
git merge local-branch --- наложить изменения из локальной ветки в текущую
git checkout -b local-branch remotes/origin/master --- скачать ветку с удаленного репозитория и переключиться на нее
git remote add username-project git@github.com:username/project.git --- добавление ссылки на удаленный репозиторий
git remote update --- обновить информацию о удаленном репозитории
git reset HEAD~10 --- откатить форк на нужное количество коммитов
