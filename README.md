# ansible-certbot

[certbot](https://github.com/certbot/certbot) is EFF's tool to obtain certs from Let's Encrypt

[![Licence](https://img.shields.io/badge/Licence-MIT-blue.svg)](https://tldrlegal.com/license/mit-license)
[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)[![Build Status](https://travis-ci.org/telusdigital/ansible-certbot.svg?branch=master)](https://travis-ci.org/telusdigital/ansible-certbot)

Tunables
--------
* ```certbot_domain``` (string) -
* ```certbot_agree_tos``` (boolean) -
* ```certbot_keep_until_expiring``` (boolean) -
* ```certbot_email``` (string) -
* ```certbot_source``` (string) -

* ```certbot_owner``` (string) -
* ```certbot_group``` (string) -

* ```certbot_name``` (string) -
* ```certbot_path``` (string) -
* ```certbot_combined``` (boolean) -
* ```certbot_path_public``` (string) -
* ```certbot_path_private``` (string) -
* ```certbot_path_combined``` (string) -
* ```certbot_certificate_path``` (string) -
* ```certbot_web_server``` (string) -

* ```certbot_dry_run``` (boolean) -

Dependencies
------------
* None

Example Playbook
----------------
    - hosts: servers
      roles:
         - role: telusdigital.certbot

Contributors
------------
* Steven Harradine
* [Aaron Pederson](https://aaronpederson.github.io/) | [e-mail](mailto:aaron.pederson@gmail.com) | [Twitter](https://twitter.com/GunFuSamurai)
* Alex Podobnik | [e-mail](mailto:alexandar.podobnik@gmail.com)
