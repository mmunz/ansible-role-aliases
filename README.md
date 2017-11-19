c1.aliases
==========

update mail aliases database

This is a fork of https://github.com/xcezx/ansible-aliases which seems unmaintained.

Role Variables
--------------

- `aliases`

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: c1.aliases
           aliases:
             - user: root
               alias: john.doe@example.com

License
-------

BSD
