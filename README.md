Install Vector
=========

This role for install Vector

Role Variables
--------------

vector_version: version vector

Example Playbook
----------------

    - hosts: server
      roles:
         - { role: vector-role }

Tests
----------------
Molecule(OS centos7, centos8, ubuntu:latest):

```
molecule test
```
Tox:
```
docker run --privileged=True -v <path_to_repo>:/opt/vector-role -w /opt/vector-role -it aragast/netology:latest /bin/bash
```
In container:
```
tox
```

License
-------

MIT

Author Information
------------------

Krasichkov Aleksandr
