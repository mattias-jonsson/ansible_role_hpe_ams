Ansible Role: ansible_role_hpe_ams
=========

Installs/upgrades HPE AMS service on the following Linux distributions:

<ul>
<li>Red Hat Enterprise Linux 7
<li>Red Hat Enterprise Linux 8
</ul>


Requirements
---------------

None.

Role variables
---------------

None.


Dependencies
------------

Depends on https://github.com/mattias-jonsson/ansible_role_hpe_spp_repo


Example Playbook
----------------


    - hosts: servers

      roles:
         - ansible_role_hpe_ams

License
-------

MIT

Author Information
------------------

Mattias Jonsson
