# devops-netology
# Senibratov Vyacheslav

# Локальная  директория .terraform попадает в игноируемые.
**/.terraform/*

# Файлы с расширением .tfstate  и файлы содержащие в названии tfstate
*.tfstate
*.tfstate.*

# Crash лог файлы игнорируются
crash.log
crash.*.log

# Игнорировать все файлы которые могут содержать пароли и конфиденциальные данные
*.tfvars
*.tfvars.json

# Игнорируются файлы
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Игнорировать CLI конфигурационные файлы
.terraformrc
terraform.rc
