Role Ansible PHP
=========

![ansible-php](https://img.shields.io/github/issues/spy86/ansible-php.svg) ![ansible-php](https://img.shields.io/github/forks/spy86/ansible-php.svg) ![ansible-php](https://img.shields.io/github/stars/spy86/ansible-php.svg) ![ansible-php](https://img.shields.io/github/license/spy86/ansible-php.svg) ![ansible-php](https://img.shields.io/twitter/url/https/github.com/spy86/ansible-php.svg?style=social)

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
