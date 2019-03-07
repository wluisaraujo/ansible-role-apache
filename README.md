[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-webserver.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-webserver)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Apache WebServer](https://www.apache.org/)
------------

Description
------------

 *

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - iac-ansible-webserver
```

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
