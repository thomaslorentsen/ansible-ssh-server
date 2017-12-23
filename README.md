[![Build Status](https://travis-ci.org/thomaslorentsen/ansible-ssh-server.svg?branch=master)](https://travis-ci.org/thomaslorentsen/ansible-ssh-server)

Ansible SSH Server
=========

Installs an ssh server and configures it

Requirements
------------



Role Variables
--------------


| Var | Default | Description |
| --- | --- | --- |
|  ```ssh_daemon``` | ```ssh``` | SSH service name |
|  ```ssh_allowed_users``` | ```tom``` | SSH service name |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: thomaslorentsen.ssh-server }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
