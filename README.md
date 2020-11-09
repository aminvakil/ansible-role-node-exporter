Role Name
=========

Ansible Node Exporter

Requirements
------------

None.

Role Variables
--------------

`node_exporter_version` which currently is the latest version (1.0.1).

`node_exporter_interface` specifies the interface(s) node-exporter will listen on.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      become: true
      roles:
         - role: aminvakil.node_exporter

License
-------

MIT

Author Information
------------------

[Amin Vakil](https://www.aminvakil.com/)
