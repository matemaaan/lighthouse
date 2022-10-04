Role Name
=========

Role lighthouse

Requirements
------------

Role Variables
--------------

The git repo of lighthouse to install.

  lighthouse_vcs: https://github.com/VKCOM/lighthouse.git

Dependencies
------------

You must first perform the role!

- name: nginx
  src: git@github.com:PanMonsters/roles_nginx.git
  scm: git

This role will install nginx required for lighthouse to work!

Example Playbook
----------------

    - name: Install Lighthouse
      hosts: lighthouse
      roles:
        - lighthouse

License
-------

MIT

Author Information
------------------

matemaaan
