Role Name
=========

This docker role builds on geerlingguy.docker to install python-pip and docker-py so that
ansible playbooks can use docker_containers and docker_image modules.

Source available at https://github.com/liangsuno/ansible-role-docker.

Dependencies
------------

This role depends on geerlingguy.docker.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: liangsuno.docker }

License
-------

BSD

Author Information
------------------

This role was created in Oct 2017 by Ooi Liang Sun <liangsun@gmail.com>.
