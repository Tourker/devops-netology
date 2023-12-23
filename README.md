# devops-netology
В файле .gitignore буду исключены следующие файлы:
Директории: 
**/.terraform/*

Файлы .tfstate:
*.tfstate
*.tfstate.*

Логи: 
crash.log
crash.*.log

Файлы переменных:
*.tfvars
*.tfvars.json

Предопределенные файлы локальных ресурсов:
override.tf
override.tf.json
*_override.tf
*_override.tf.json

Файлы конфигурации:
.terraformrc
terraform.rc

New string for HW02-git-02-base
