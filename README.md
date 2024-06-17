`Ansible` роль для установки `Prometheus node exporter`
------------

Пример использования:
```
---
- name: Install Node Exporter
  hosts: nodes
  become: true
  roles:
    - role: ansible-role-node-exporter

```
