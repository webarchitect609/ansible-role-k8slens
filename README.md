Ansible Role: K8s Lens
======================

[![Build Status](https://github.com/webarchitect609/ansible-role-k8slens/actions/workflows/build.yml/badge.svg)](https://github.com/webarchitect609/ansible-role-k8slens/actions/workflows/build.yml)
[![Latest version](https://img.shields.io/github/v/tag/webarchitect609/ansible-role-k8slens?sort=semver)](https://github.com/webarchitect609/ansible-role-k8slens/releases)

[![Downloads](https://img.shields.io/ansible/role/d/webarchitect609/k8slens)](https://galaxy.ansible.com/ui/standalone/roles/webarchitect609/k8slens)
[![License](https://img.shields.io/github/license/webarchitect609/ansible-role-k8slens)](LICENSE.md)
[![More stuff from me](https://img.shields.io/badge/galaxy-webarchitect609-000)](https://galaxy.ansible.com/ui/standalone/namespaces/7493/)

Installs [Lens IDE](https://k8slens.dev/) for K8s from the official apt repo.

Requirements
------------

None.

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - { role: webarchitect609.k8slens }
```

License & Author Information
----------------------------

[BSD-3-Clause](LICENSE.md)
