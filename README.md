[![](https://github.com/samples-mamono210/cowsay/workflows/build/badge.svg)](https://github.com/samples-mamono210/cowsay/actions?query=workflow%3Abuild)

Role Description
=========

Installs [Cowsay](https://github.com/tnalpgge/rank-amateur-cowsay) for CentOS Stream 8.

Requirements
------------

[EPEL](https://docs.fedoraproject.org/en-US/epel/) installed before running this role.

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
    - geerlingguy.epel
    - cowsay
```

License
-------

BSD
