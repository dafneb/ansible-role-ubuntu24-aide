AIDE on Ubuntu 24
=================

An Ansible role to install AIDE on Ubuntu 24.

Requirements
------------

No special requirements. Some tasks require "privileged role" at system. So, use [become](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_privilege_escalation.html#using-become) option at your inventory list.

Role Variables
--------------

This role is designed so the end user should not have to edit the tasks themselves. All customizing should be done via the defaults/main.yml file or with extra vars within the project, job, workflow, etc.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: dafneb.ubuntu24-aide }

License
-------

MIT

