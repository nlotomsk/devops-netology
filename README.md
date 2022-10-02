# devops-netology
## Senibratov Vyacheslav

#### Локальная  директория .terraform попадает  игноируется.
```
**/.terraform/*
```

#### Файлы с расширением .tfstate  и файлы содержащие в названии tfstate
```
*.tfstate
*.tfstate.*
```

#### Crash лог файлы игнорируются
```
 crash.log
 crash.*.log
```

#### Игнорировать все файлы которые могут содкржать пароли и конфиденциальные данные
```
- *.tfvars
- *.tfvars.json
```

#### Игнорируются файлы
```
1. override.tf
2. override.tf.json
3. *_override.tf
4. *_override.tf.json
```

#### Игнорировать CLI конфигурационные файлы
```
- [x] .terraformrc
- [ ] terraform.rc
```