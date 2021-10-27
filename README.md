ansible-rundeck
=========

Role to deploy rundeck

Requirements
------------

None

Role Variables
--------------

More details for variable could be found in default/main folder

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: rundeck
  roles:
    - { role: dorancemc.ansible-rundeck, tags: [ rundeck ] }  
```

License
-------

Apache-2.0

Author Information
------------------

Dorance Martinez @dorancemc
