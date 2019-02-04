web_app_role
=========

Ansible role for starting web-applications

Requirements
------------

This role use image from private Docker Hub repository

Role Variables
--------------

None

Dependencies
------------

This role use role for installing and configuring Docker: konstantin009.docker_role

Example Playbook
----------------

    - hosts: all
      roles:
         - role: web_app_role

License
-------

BSD
