# devops-netology
Изменение в ветке fix
new line

Благодаря добавленному файлу .gitignore в каталог Terraform будут проигнорированы файлы:
-Локальная .terraform директория, где бы она ни находилась
-Файлы .tfstate (похоже, файлы состояния)
-Логи крахов
-Файлы .tfvars, .tfvars.json, в которых содержатся конфиденциальные данные (пароли, приватные ключи и т.п.)
-Группа файлов override.tf, используемых для локального переопределения ресурсов
-Конфигурационные файлы командной строки
