almaops.ct_elasticsearch
==========

This role deploys elasticsearch in docker container. Single-node only.

Requirements
------------

Role: [almaops.docker](https://galaxy.ansible.com/almaops/docker)

Role Variables
--------------

Look into [./defaults/main.yml](./defaults/main.yml)

Example Playbook
----------------

```
- hosts: servers
  roles:
    - role: almaops.ct_elasticsearch
```

License
-------

[MIT License](./LICENSE)


Author Information
------------------
Dmitrii Kashin, <freehck@freehck.com>
