Role Ansible PHP
=========

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Role to install PHP

Requirements
------------
None

Role Variables
--------------

- `php5_composer` - This option is enabled by default
- `php5_extensions` - List of extensios which will be installed. Default this is: `curl, gd, intl, mcrypt, mysql, redis, xcache`

Dependencies
------------

None

Example Playbook
----------------

```yaml
---
- hosts: servers
  remote_user: root
  roles:
   - role: ansible-php

```
