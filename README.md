Packages
========

Installs required and common system packages

Requirements
------------

None

Role Variables
--------------

- **packages_upgrade**: false

Dependencies
------------

- [ryanlelek.providers](https://galaxy.ansible.com/ryanlelek/providers/)

Example Playbook
----------------

    - hosts: all
      roles:
         - ryanlelek.providers
         - ryanlelek.packages

License
-------

MIT

Author Information
------------------

Created by [Ryan Lelek](https://www.ryanlelek.com)  
Part of [AnsibleTutorials.com](http://www.ansibletutorials.com)
