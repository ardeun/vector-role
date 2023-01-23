Role Name
=========

Роль для установки vector

- Установка vector
- Создание systemd unit Vector
- Настройка конфигурации vector

Requirements
------------

Требует наличия установленного сервера clickhouse

Role Variables
--------------

версия vector

```yaml
vector_version: "0.25.1"
```

данные для подключения к серверу clickhouse

```yaml
clickhouse_user: netology
clickhouse_password: netology
clickhouse_host: 127.0.0.1
```

конфигурация логов прописана в vars/main.yml

Dependencies
------------

Example Playbook
----------------

```yaml
    - hosts: vector
      roles:
         - vector_role
```

License
-------

BSD

Author Information
------------------
