Ansible Role: certbot-python27-scl
==================================

set renew cron by python27-scl after install certbot by geerlingguy.certbot.

Requirements
------------

TBD

Role Variables
--------------

no

Dependencies
------------

dependencies following roles:

- geerlingguy.certbot
- tyoshii.python27-scl

Example Playbook
----------------

    - hosts: servers
      roles:
         - tyoshii.certbot-python27-scl

License
-------

MIT / BSD
