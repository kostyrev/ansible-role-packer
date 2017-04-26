# packer

[![Build Status](https://travis-ci.org/kostyrev/ansible-role-packer.svg?branch=master)](https://travis-ci.org/kostyrev/ansible-role-packer)

Installs packer

Requirements
------------

None

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml) for a list and description of
variables used in this role.

Example Playbook
----------------

```yaml
---
- hosts: localhost
  connection: local
  roles:
    - kostyrev.packer

```

Install From Github
-------------------

```
git clone https://github.com/kostyrev/ansible-role-packer.git kostyrev.packer
cd kostyrev.packer && make install
```

License
-------

BSD

Author Information
------------------

Aleksandr Kostyrev
