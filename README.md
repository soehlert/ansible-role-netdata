Role Name
=========

A role for installing Netdata.

Requirements
------------

Uncomment the last task in tasks/main.yml if you are on Ansible 2.2 (Daemon config) and comment out the second to last task (Service stuff). Leave commented out if you are on any version before that.

Role Variables
--------------

N/A

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: soehlert.netdata }

License
-------

BSD

Author Information
------------------

https://samoehlert.com
