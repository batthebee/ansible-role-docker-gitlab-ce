docker-gitlab-ce
=================

Ansible role to setup [sameersbn/docker-gitlab](https://github.com/sameersbn/docker-gitlab) with docker-compose


Requirements
------------

TODO

Role Variables
--------------

All Variables are prefixed with 'gitlab_'.

Setup container destination:

gitlab_container_name - docker name of gitlab instance
gitlab_container_home - destination on target where to install the container

Setup container:

For all aviable Variables see: [sameersbn/docker-gitlab](https://github.com/sameersbn/docker-gitlab)

all variables needs to be prefixed by 'gitlab_'.
i.e. 'gitlab_db_user' needs to be 'gitlab_gitlab_db_user'


Dependencies
------------

TODO

Example Playbook
----------------

TODO

License
-------

GPLv3

Author Information
------------------

TODO
