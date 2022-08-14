# Ansible Collection - artem_salnikov.my_own_collection

Эта коллекция содержит модуль и роль для использования модуля.  
Модуль создает файл по заданному пути с наполнением в виде заданного текста.

Роль будет работать на большинстве ОС Linux.

Role Variables
--------------
Вы можете изменить следующие переменные:  
dest_path: /tmp/my_file  
content: netology

Example Playbook
----------------
```
- hosts: <IP>
  collections:
    - artem_salnikov.my_own_collection
```