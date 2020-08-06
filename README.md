Role opensim-workbench
======================

This role installs and configures all packages needed on the opensim workbech host ( localhost ). 

Requirements
------------

- none

Role Variables
--------------

- none

Dependencies
------------

- none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```YAML
---
- hosts: localhost
  become: yes
  gather_facts: yes

  roles:
    - opensim-workbench
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
