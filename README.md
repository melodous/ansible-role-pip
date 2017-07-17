Welcome to pip Ansible Role’s documentation!
============================================

Role Name
---------

This role install pip software on the server, it also can configure the
proxy from pypi.

### Requirements

Repositories configure with pip software

### Dependencies

N/A

### Example Playbook

    - hosts: servers
      roles:
        - { role: pip }

pip ansible role default variables
----------------------------------

#### Sections

-   pip management

### pip management

`pip_proxy`

> pip proxy address

    pip_proxy: false

Example:

    pip_proxy: artifactory.yourdomain.com

`pip_proxy_url`

> pip proxy index url

    pip_proxy_url: false

Example:

Changelog
---------

**pip**

This project adheres to Semantic Versioning and human-readable
changelog.

### pip master - unreleased

##### Added

-   First addition

##### Changed

-   First change

### pip v0.0.2 - 2017/07/17

##### Changed

-   Fixed configure without proxy

### pip v0.0.2 - 2017/07/13

##### Added

-   Fixed doc
-   Fixed ansible lint

### pip v0.0.1 - 2017/07/12

##### Added

-   Initial version

Copyright
---------

pip

Copyright (C) 2017/07/12 Raúl Melo
&lt;<raul.melo@opensolutions.cloud>&gt;

LICENSE
