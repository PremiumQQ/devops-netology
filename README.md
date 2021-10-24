
# devops-netology

**/.terraform/* - локальные директории будут проигнорировваны.

*.tfstate - файлы типа .tfstate будут проигнрированы.

crash.log - игнрирование логов ошибок.

*.tfvars - игнрирование секретных ключей и паролей.

override.tf
override.tf.json
*_override.tf
*_override.tf.json - игнрирование файлов, которые переопределяют формат.

.terraformrc
terraform.rc  - игнорирование конфигурационных файлов.
