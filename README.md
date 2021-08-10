Ansible Role: DB Check
=========

A simple role to check if Oracle of SQL Server is installed on a Windows or Linux machine.

Example Playbook
----------------
```yaml
---
- name: Check for installed DBs
  hosts: all
  roles
    - ckstevenson.db-check
```
## License
MIT
