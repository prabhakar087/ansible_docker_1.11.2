docker-engine
=========

docker-engine is an ansible role to install docker engine on centOS/RedHat 7.

Role Variables
--------------

Following variables have been used in the docker-engine role.
docker_engine_cache_valid_time   # cache_valid_time for apt
dockerVersion

Default Variables
--------------

Following variables have been used in the docker-engine role.
docker_engine_cache_valid_time: 84600   # cache_valid_time for apt
dockerVersion: 1.12

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: docker-engine }

License
-------

BSD

Author Information
------------------

Prabhakar Kashyap DevOps at OpsTree Solutions.
