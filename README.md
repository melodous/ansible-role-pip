Welcome to pip Ansible Role’s documentation!
============================================

Role Name
---------

A brief description of the role goes here.

### Requirements

Any pre-requisites that may not be covered by Ansible itself or the role
should be mentioned here. For instance, if the role uses the EC2 module,
it may be a good idea to mention in this section that the boto package
is required.

### Dependencies

A list of other roles hosted on Galaxy should go here, plus any details
in regards to parameters that may need to be set for other roles, or
variables that are used from other roles.

### Example Playbook

Including an example of how to use your role (for instance, with
variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - { role: username.rolename, x: 42 }

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

    pip_proxy_url: http://artifactory.yourdomain.com/artifactory/api/pypi/MyPyPi/simple

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

### pip v0.0.0 - DATE

##### Added

-   Initial version

Copyright
---------

pip

Copyright (C) DATE User/Company &lt;<email@email.com>&gt;

LICENSE
