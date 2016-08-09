ansible-role-dellomsa
=========

This role will install and enable the Dell OMSA tools for install on CentOS/RHEL

Requirements
------------

Obviously a Physical install on a Dell Server (Poweredge, etc) is the only way this can be used.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: dell_servers
      roles:
         - { role: ansible-role-dellomsa, x: 42 }

License
-------

BSD

Author Information
------------------

Shannon Carver (shannon.carver@gmail.com)
