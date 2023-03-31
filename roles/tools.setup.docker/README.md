Service Role
=========

Installs and configures docker, docker-compose on amazon linux 2.

Requirements
------------

ansible version: `2.9.23`

docker-ce version: `20.10.17`

Role Variables
--------------

You can set the following variables to `vars/main` or `defaults/main.yml`, an example is listed below:
**DOCKER_COMPOSE_VERSION: "v2.2.2"**

This role doesn't make use of other roles. Thus there's not variables set under `hostvars` or `group vars` for now.

Future Improvements
-------------------

This role needs your active support, however future versions of this role will have the following:

- Ability to detect OS version using `ansible_facts` and run different playbooks accordingly.
- More handlers incoming.
- Better package management.
- Part of being a collection for devops roles. 


That's all folks!