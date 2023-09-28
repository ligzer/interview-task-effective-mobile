# Задание 1

Разработать ansible, запускающий докеризированное веб приложение (nginx, php, mysql) с использованием docker-compose.yml на удалённом сервере.
Плейбук должен
1. Дистрибьютить необходимые для работы файлы
2. Генерировать конфигурационный файл для nginx, и, по необходимости,
перезапускать его (nginx).

Результатом выполнения ТЗ является:
1. Ansible playbook (вместе с ролями и/или файлом с зависимостями, необходимыми
шаблонами);
2. docker-compose.yml;
3. Dockerfile;

# Readme
First install requirements
```shell
ansible-galaxy install -r requirements.yml
```
Config ansible inventory and run playbook
```shell
ansible-playbook Playbook.yml
```

