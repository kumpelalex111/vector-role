Role Vector
=========

This role install vector v.0.53.0 

Requirements
------------
Requires a Linux Ubuntu 24 or higher operating system

Role Variables
--------------

The vector_config_dir variable by default points to the directory "{{ ansible_user_dir }}/vector_config"

Example Playbook
----------------

An example of launching a playbook: 

    - hosts: servers
      roles:
         - vector

License
-------

BSD


