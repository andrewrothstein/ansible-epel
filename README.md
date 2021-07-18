andrewrothstein.epel
===========================
![Build Status](https://github.com/andrewrothstein/ansible-epel/actions/workflows/build.yml/badge.svg)

A role for installing [Extra Packages For Enterprise Linux](https://fedoraproject.org/wiki/EPEL)

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.epel
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
