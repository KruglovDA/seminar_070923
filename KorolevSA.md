# Руководство пользователя по работе с Git
## 1.Основные команды
* git init - инициализирует репозиторий
* git config --global user.name  - присвоить имя
* git config --global user.email
* git config --global credential.helper cache - кэширование файла
## 2. Работа с ветками
* git branch branch_name - содаёт ветку с именем branch_name
* git branch - показывает список веток
* git merge Feature_branch - объединяем изменения из другой ветки
* git checkout main - переключитесь на ветку, в которую вы хотите внести изменения