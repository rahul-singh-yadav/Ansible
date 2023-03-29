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

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

How to use this role
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
