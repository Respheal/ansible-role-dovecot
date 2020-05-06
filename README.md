inmotionhosting.dovecot
=========

Modular Ansible Role for deploying and configuring Dovecot

[![Build Status](https://travis-ci.org/inmotionhosting/ansible-role-dovecot.png?branch=master)](https://travis-ci.org/inmotionhosting/ansible-role-dovecot)

Requirements
------------

* CentOS 7.x or later
* Debian 9 or later
* Ubuntu 16.04.x LTS or later

Role Variables
--------------

| Variable | Description |
| -------- | ----------- |

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: www
      roles:
         - role: inmotionhosting.dovecot

License
-------

GPLv3

Author Information
------------------

[InMotion Hosting](https://inmotionhosting.com)
