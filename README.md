[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-Apache-blue.svg)](https://galaxy.ansible.com/wluisaraujo/apache) [![Build Status](https://travis-ci.com/wluisaraujo/ansible-role-apache.svg?branch=master)](https://travis-ci.com/wluisaraujo/ansible-role-apache)

# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Apache WebServer](https://www.apache.org/)
------------

Description
------------

 *

Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.apache
vagrant@localhost:~$ ansible-galaxy install -r wluisaraujo.apache/requirements.txt
```

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
    - apache
...    
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
