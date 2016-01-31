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

Do Not Upgrade Packages:  

    - hosts: all
      roles:
         - ryanlelek.providers
         - ryanlelek.packages

Upgrade Packages:

    - hosts: all
      roles:
         - ryanlelek.providers
         - role: ryanlelek.packages
           packages_upgrade: true

License
-------

MIT

Author Information
------------------

Created by [Ryan Lelek](https://www.ryanlelek.com)  
Part of [AnsibleTutorials.com](http://www.ansibletutorials.com)
