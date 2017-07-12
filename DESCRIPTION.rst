Role Name
=========

This role install pip software on the server, it also can configure the proxy from pypi.

Requirements
------------

Repositories configure with pip software

Dependencies
------------

N/A

Example Playbook
----------------

.. code::

  - hosts: servers
    roles:
      - { role: pip }
