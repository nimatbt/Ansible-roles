Role Name
=========

Install and config Nginx on remore hosts

Requirements
------------

You can find requirements in requirements.txt

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Please use config tag in ansible-playbook for only copy nginx.conf and default.conf 

    - ansible-playbook -b -t config -i inventory.ini playbook.yaml


License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
