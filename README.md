Ansible Role - protobuf
=====================

This playbook installs [protobuf](https://developers.google.com/protocol-buffers/).

Platforms
---------

CentOS 6.7 is the only platform that is supported and tested so far.

Role Variables
--------------

- Check out [defaults/main.yml](defaults/main.yml)

Dependencies
------------

None.

Installation
------------

Regular installation:

```
ansible-galaxy install RDI2.protobuf
```

Installation to a specific directory(e.g. roles/):

```
ansible-galaxy install -p roles/ RDI2.protobuf
```

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: RDI2.protobuf }

License
-------

MIT License.

Author Information
------------------

- Koji Tanaka, RDI2
