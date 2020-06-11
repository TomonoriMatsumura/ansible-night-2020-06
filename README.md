[![](https://github.com/TomonoriMatsumura/ansible-night-2020-06/workflows/playbook/badge.svg)](https://github.com/TomonoriMatsumura/ansible-night-2020-06/actions?query=workflow%3Aplaybook)

Role Description
=========

Installs [Cowsay](https://github.com/tnalpgge/rank-amateur-cowsay) for CentOS7.

Requirements
------------

EPEL installed before running this role.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - geerlingguy.repo-epel
    - cowsay
```

License
-------

BSD
