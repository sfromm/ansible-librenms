librenms
=========

Ansible role to manage [librenms](http://librenms.org).

LibreNMS is an autodiscovering PHP/MySQL/SNMP based network monitoring
which includes support for a wide range of network hardware and
operating systems including Cisco, Linux, FreeBSD, Juniper, Brocade,
Foundry, HP and many more.

Requirements
------------

No external dependencies.

Role Variables
--------------

TODO

Dependencies
------------

No dependency on other roles.

Example Playbook
----------------

A trivial example:

    - hosts: nms
      roles:
        - role: sfromm.librenms
          librenms_devices:
            - db1.example.com
            - db2.example.com
            - core-sw.example.com
            - core-gw.example.com
            - car-gw.example.com
            
License
-------

GPLv2

Author Information
------------------

See https://github.com/sfromm
