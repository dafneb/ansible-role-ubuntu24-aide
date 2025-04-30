AIDE on Ubuntu 24
=================

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](https://github.com/dafneb/.github/blob/main/.github/CODE_OF_CONDUCT.md) 
[![License](https://img.shields.io/badge/License-MIT-4baaaa.svg)](https://github.com/dafneb/.github/blob/main/LICENSE)
![GitHub Release](https://img.shields.io/github/v/release/dafneb/ansible-role-ubuntu24-aide)
![GitHub commit activity](https://img.shields.io/github/commit-activity/w/dafneb/ansible-role-ubuntu24-aide)
![GitHub contributors](https://img.shields.io/github/contributors/dafneb/ansible-role-ubuntu24-aide)

![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/dafneb/ansible-role-ubuntu24-aide/ansible-lint.yml?label=ansible-lint)

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

