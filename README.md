# devops-netology

Репозиторий для курса devops на netology.ru

Gitignore terraform
Будут исключены из подпапки terraform:
1) скрытая папка .terraform во всех подкаталогах
2) файлы, содержащие в расшиернии элементы .tfstate .tfstate. .tfvars
3) файлы, оканчивающиеся на _override.tf _override.tf.json
4) файлы crash.log override.tf override.tf.json .terraformrc terraform.rc

Изменения ветки fix