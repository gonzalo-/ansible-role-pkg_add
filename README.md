pkg_add
=========

Easy way to install all you need with one command on a OpenBSD fresh (or nasty) system.

Requirements
------------

OpenBSD, doas (become_method) permissions.

Dependencies
------------

pkg_add(1) already take care of it. Also to set a installurl file.

Example Playbook
----------------

    - hosts: server
      roles:
         - role: ansible-role-pkg_add

License
-------

BSD
