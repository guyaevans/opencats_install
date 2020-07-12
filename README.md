Install OpenCATS
=========

This is a role to install OpenCATS source files

Requirements
------------

The role is build for Ubuntu may work on others but untested

Role Variables
--------------

no variables are required

Dependencies
------------

This roles requires:
    - geerlingguy.apache
    - geerlingguy.php-versions
    - geerlingguy.php
    - geerlingguy.php-mysql
    - geerlingguy.mysql

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: guyaevans.opencats}

License
-------

BSD 3


