Role Name
=========

Debian Wheezy Standalone Server Base

Requirements
------------

Debian Wheezy minimal installation.

Role Variables
--------------

 - wheezy_server_base_mirror: http://ftp.de.debian.org/debian

Firewll settings
================

external interface:
wheezy_server_base_ext_if: eth0

does it get its ip via dhcp?:
wheezy_server_base_ext_if_dhcp: 0

Dependencies
------------

- working mail, e.g. mailx

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: geromueller.wheezy-server-base }

License
-------

BSD

Author Information
------------------

Gero Müller <post@geromueller.de>
