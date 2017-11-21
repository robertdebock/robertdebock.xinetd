ansible-role-xinetd
=========

Provides xinetd for your system.

Requirements
------------

Access to a repository containing packages, likely on the internet.

Role Variables
--------------

None known.

Dependencies
------------

- robertdebock.ansible-role-bootstrap

Example Playbook
----------------

```
- hosts: servers

  roles:
    - robertdebock.ansible-role-xinetd

```

License
-------

Apache License, Version 2.0

Author Information
------------------

Robert de Bock <robert@meinit.nl>
