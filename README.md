Ansible roles for docker swarm: initialize swarm mode
=========

Initialize swarm mode and create base networks.

Just switching docker to swarm mode and creating the necessary networks for web services.

Requirements
------------

Docker must be installed.

Can install docker using role https://github.com/ansible-roles-for-docker-swarm/docker

Role Variables
--------------

`public_network_name`: the name of the public docker network to be created.

Dependencies
------------

No dependencies.

Example Playbook
----------------

```
- hosts: servers
  roles:
    - role: swarm
      tags:
        - swarm
```

License
-------

GPL-3.0-only

Author Information
------------------

Nothing.