Install MySQL
=========

This role install MySQL

Requirements
------------

Python must be installed.

Dependencies
------------

Python must be installed.
- name: Install Dependencies
  yum:
    state: present
    name:
    - "epel-release"
    - "oracle-epel-release-el8"
    - "python3"
    - "python3-devel"

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - mysql_db

License
-------

BSD

Author Information
------------------

KG
