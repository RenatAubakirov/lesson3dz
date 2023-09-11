# Инструкция по Git #
## 1. Установка Git #
* скачать программу git с официального сайта 
* установить git на свой компьютер
* Запустить git_bash
## 2. Настройка Git #
**все команды начинаются со слова git ....**
* Прописываем емаил и ФИО
 * git config --global user.name "BBB"
 * git config --global user.email йййй@mail.ru 
## 3. Основные команды #
* git init – инициализация локального репозитория
* git status – получить информацию от git о его текущем состоянии 
* git add – добавить файл или файлы к следующему коммиту
* git commit -m “message” – создание коммита.
* git log – вывод на экран истории всех коммитов с их хеш-кодами
* git branch – посмотреть список веток в репозитории
* git branch <название ветки> – создать новую ветку
* git checkout <название ветки> – переход к другой ветке
* git branch -d <название ветки> – удалить ветку
## 5. GIThub команды #
* git clone <url-адрес репозитория> – клонирование внешнего репозитория на
локальный ПК
* git pull – получение изменений и слияние с локальной версией
* git push – отправляет локальную версию репозитория на внешний
## 6.Работа с удалёнными репозиториями ##
* Создать аккаунт на GitHub
* Создать локальный репозиторий
* Создать удалённый репзиторий
* Связать удалённый репозиторий с локальным
* Добавить удалённый репозиторий к проекту:

git remote add <имя для репозитория> <url-адрес репозитория в сети>
* Для получения и слияния изменений из удалённого репозитория используется команда git pull
* Отправить изменения локального репозитория в удалённый git push