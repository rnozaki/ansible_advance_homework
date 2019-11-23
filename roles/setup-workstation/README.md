Role Name
=========

This role sets up the workstation:
- include_tasks: pre-tasks.yml
- include_tasks: create-flavor.yml
- include_tasks: create-keypair.yml
- include_tasks: create-sg.yml
- include_tasks: create-image.yml
- include_tasks: create-network.yml

Requirements
------------

It depends on network access from bastion to the workstation and keys properly assigned for access.

Role Variables
--------------

Variables used are defined in the vars dir.

Author Information
------------------

By: Roberto Nozaki
