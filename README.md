xinetd
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

- robertdebock.bootstrap

Example Playbook
----------------

```
- hosts: servers

  roles:
    - robertdebock.xinetd

  tasks:
    - name: likely nothing but include other roles, like robertdebock.tftpd
      ping:
```

License
-------

Apache License, Version 2.0

Author Information
------------------

Robert de Bock <robert@meinit.nl>
