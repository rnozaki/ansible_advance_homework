Role Name
=========

This role provisions the osp instances to be installed.
- include_tasks: create-image.yml
- include_tasks: create-flavor.yml
- include_tasks: create-keypair.yml
- include_tasks: create-network.yml
- include_tasks: create-sg.yml

Requirements
------------

It depends on the servers being ready at the moment of the execution.

Role Variables
--------------

Variables used are all defined in the vars directory

Author Information
------------------

By: Roberto Nozaki
---
