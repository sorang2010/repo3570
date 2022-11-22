# repo3570
## geekbrains/Introdution to git/ lecture 3


# Инструкция по работе с Git #
## Лекция 1
### Перед первым запуском Git выполнить команды ###
1. git config --global user.email "you@example.com"
2. git config --global user.name "Your Name"

### Проверка почты и имени ###
1. git config --global user.email
2. git config --global user.name

## 1 Создаем репозиторий 
**git init**
## 2 Добавляем файлы в репозиторий
**git add filename** - добавили файл с именем *filename*
## 3 Каждое добавление файлов следует зафиксировать коментарием
таким образом указывается, что за информацию фиксируем: **git commit -m "text"**
*где '-m' - от англ. message*
## 4 вывод на экран истории всех коммитов с их хеш-кодами
**git log**
## 5 Переход от одного коммита к другому
**git checkout**
## 6 Вернуться к актуальному состоянию и продолжить работу
**git checkout master**
## 7 Просмотр разницы между текущим файлом и закоммиченным файлом
**git diff**

Ссылка на документацию по работе с языком Markdown - <https://texterra.ru/blog/ischerpyvayushchaya-shpargalka-po-sintaksisu-razmetki-markdown-na-zametku-avtoram-veb-razrabotchikam.html>

картинка с котиком - ![](/home/admin1/Dev22/test_git1/cat04.jpg)

## Лекция 2
## 8 Получение информации от git о его текущем состоянии
**git status**
## 9 Вывод на экран истории всех коммитов с их хеш-кодами
**git log**
## 10 Вывод на экран списка веток в репозитории
**git branch**
## 11 Создание новой ветки
**git branch <название ветки>**
## 12 Удаление ветки
**git branch -d <название ветки>**

## Лекция 3
## 13 клонирование внешнего репозитория на  локальный ПК
**git clone <url-адрес репозитория>**
## 14 получение изменений и слияние с локальной версией
**git pull**
## 15 отправляет локальную версию репозитория на внешний
**git push**