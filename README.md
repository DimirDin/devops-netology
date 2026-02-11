# devops-netology
TEST TEST

## Terraform .gitignore

В директории `terraform/` будут игнорироваться следующие файлы:

- `*.tfstate` и `*.tfstate.*` — файлы состояния Terraform
- `crash.log` — логи падений
- `*.tfvars` — файлы с переменными (часто содержат секреты)
- `override.tf`, `override.tf.json` и файлы вида `*_override.tf`, `*_override.tf.json` — файлы переопределений
- `.terraform/` — директория с плагинами и модулями
- `.terraform.lock.hcl` — файл блокировки провайдеров
