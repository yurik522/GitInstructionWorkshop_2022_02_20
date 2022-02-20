# Инструкция по работе с git

## Что это и для чего нужна система контроля версий?

### Что такое система контроля версий?

### Для чего нужна система контроля версий

## Установка git и VSCode на ваш ПК.

### Установка VSCode на ваш ПК.

### Установка git на ваш ПК

#### Первая настройка git

## Создание и базовая работа с локальным репозиторием.

### Что такое репозиторий и инструкция по созданию локальных репозиториев.

### Базовая работа с локальным репозиторием

## Ветки. Локальная работа с ветками в git.

### Что такое ветки и для чего они нужны при работе с системой контроля версий.

### Базовая работа с ветками в git.
Merging is used in Git to piece together a branched history. The `git merge` command merges individual branches created using the `git branch` command into a single branch.
The `git merge` command combines several commit sequences into a common history. Most often, the `git merge` command is used to merge two branches. In such cases, the git merge command takes two pointers to commits (usually the last ones in the branch) and finds a parent commit common to them. Git then creates a __merge commit__ that combines the changes from both sequences selected for the merge.

Before merging, several preparatory actions should be taken so that the operation goes without problems. Use the `git status` command. This will make sure that the HEAD points to the branch receiving the merge results. If necessary, run the `git checkout <receiving_branch>` command to switch to the host branch. For example, run the `git checkout master` command.

After the above steps, you can proceed to **merge**. To do this, run the `git merge <receiving_branch>` command, where <receiving_branch> is the name of the branch that will be merged with the host (master branch as example).

## Работа с удаленными репозиториями.

### Что такое удаленный репозиторий и для чего он нужен

### Базовая работа с удаленными репозиториями GitHub

## Совместная работа над проектом (fork, pull request)

### Как строится и для чего нужна совместная работа в системах контроля версий

### Инструкция по созданию pull request

## Книги и полезные ссылки по изучению git.

## Альтернативные системы контроля версий.
