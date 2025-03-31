Kitty terminal
==============

This role installs and configures [Kitty](https://sw.kovidgoyal.net/kitty/) terminal.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example
-------

[roles-galaxy.yaml](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html#installing-multiple-roles-from-a-file)
-----------------

    ---
    - name:     kitty-terminal
      src:      rooland-provisioning.kitty-terminal
      version:  v0.0.1

Playbook
--------

    - hosts: servers
      roles:
         - kitty-terminal

License
-------

BSD

Author Information
------------------

Mailo Světel — http://mailo.svetel.cz
