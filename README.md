Ansible Role - Zabbix
=========

Installs zabbix on el8 hosts

Requirements
------------

No external requirements are required at this time.

Role Variables
--------------
Recommended variables to define:

```
zabbix_server_name: monitoring
zabbix_database_name: zabbix
zabbix_database_username: zabbix
zabbix_database_password: zabbix
```

Dependencies
------------
- community.postgresql

Example Playbook
----------------

```
roles:
  - role: silent-sysadmin.zabbix
    vars:
      zabbix_server_name: monitoring
      abbix_database_name: zabbix
      abbix_database_username: zabbix
      abbix_database_password: zabbix
```
License
-------

MIT

Author Information
------------------

silentsysadmin.com