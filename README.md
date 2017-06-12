andrewrothstein.sshd-supervisord
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-sshd-supervisord.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-sshd-supervisord)

Installs a [supervisord](http://supervisord.org/) program specification for [sshd](https://en.wikipedia.org/wiki/Secure_Shell)

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
- hosts: servers
  roles:
    - andrewrothstein.supervisord
    - andrewrothstein.sshd-supervisord
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
