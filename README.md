Role Name
=========

A role to chek for an apply updates to servers.


Requirements
------------

Only Debian supported at present

Role Variables
--------------



Dependencies
------------

None

Example Playbook
----------------


- hosts:  servers
  serial: 1
  gather_facts: true

   roles:
    - { role: ansible-applyupdates, [apt,update,packages] }


License
-------

BSD

Author Information
------------------

George Boobyer (Blue-Bag)

   # http://realguess.net/2014/12/21/ansible-update-servers-to-the-latest-and-reboot/
   # http://elnur.pro/rebooting-servers-one-by-one-with-ansible/
   # http://www.pontikis.net/blog/simple-steps-to-update-a-debian-server
