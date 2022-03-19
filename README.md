# devops-17-netology

# Local .terraform directories
**/.terraform/*
будут проигнорированы все файлы находящиеся в дериктроии .terraform

# .tfstate files
*.tfstate
*.tfstate.*
в корневой дериктории(дериктория расположения файла .gitignore) файла будут проигнорированы все файлы с расширением закнчивающимся на .tfstate
также которые начинаются как угодно, в середине tfstate, заканчиваются тоже любыми знаками.

# Crash log files
crash.log
crash.*.log
в корневой дериктории(дериктория расположения файла .gitignore) будет проигнорирован файл crash.log
и любой файл вида crash.*.log(пример crash.rar.log)

# Exclude all .tfvars files, which are likely to contain sensitive data, such as
# password, private keys, and other secrets. These should not be part of version 
# control as they are data points which are potentially sensitive and subject 
# to change depending on the environment.
*.tfvars
*.tfvars.json
будут проигнорированы все файлы в корневой дериктории(дериктория расположения файла .gitignore) с расширением закнчивающимся на *.tfvars и *.tfvars.json

# Ignore override files as they are usually used to override resources locally and so
# are not checked in
override.tf
override.tf.json
*_override.tf
*_override.tf.json
в корневой дериктории(дериктория расположения файла .gitignore) будут проигнорированы файлы  override.tf и override.tf.json
также в корневой дериктории будут проигнорированы все файлы вида *_override.tf и *_override.tf.json(пример 555_override.tf)

# Include override files you do wish to add to version control using negated pattern
# !example_override.tf

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# Ignore CLI configuration files
.terraformrc
terraform.rc
в корневой дериктории(дериктория расположения файла .gitignore) будут проигнорированы файлы конфигурации с именами  .terraformrc и terraform.rc



 new line new line new line