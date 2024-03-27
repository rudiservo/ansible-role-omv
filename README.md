Role Name
=========

Install OpenMediaVault

Requirements
------------

Debian 12

Role Variables
--------------

variables are in vars/main.yml
omv.version: 7.0
omv.release: sandworm


Dependencies
------------

No Dependencies

Example Playbook
----------------

Unless you want to install a different version of OMV you just have to use the role has instance


    - hosts: servers
      roles:
         - { omv: omv.relase = sandworm }

License
-------

GPL 2.0

Author Information
------------------

Any issues report to github.com/rudiservo/ansible-role-omv

