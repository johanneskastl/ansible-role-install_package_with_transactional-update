install_package_with_transactional-update
=========

Install a package using transactional-update on openSUSE/SUSE MicroOS or Kubic, including a reboot directly afterwards

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: 'johanneskastl.install_package_with_transactional-update' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
