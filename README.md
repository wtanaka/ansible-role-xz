[![Build Status](https://travis-ci.org/wtanaka/ansible-role-xz.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-xz)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-xz.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-xz)

wtanaka.xz
==========

Installs xz compression utilities

Example Playbook
----------------

    - hosts: servers
      roles:
         - wtanaka.xz

### `xz_should_shortcircuit`

Default: True

when True, the role short-circuits itself if xz is already installed

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
