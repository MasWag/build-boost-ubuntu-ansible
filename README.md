build-boost-ubuntu-ansible
==========================

[![Actions Status](https://github.com/MasWag/build-boost-ubuntu-ansible/workflows/Bionic/badge.svg)](https://github.com/MasWag/build-boost-ubuntu-ansible/actions?query=workflow%3ABionic)
[![Actions Status](https://github.com/MasWag/build-boost-ubuntu-ansible/workflows/Focal/badge.svg)](https://github.com/MasWag/build-boost-ubuntu-ansible/actions?query=workflow%3AFocal)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Ansible playbooks to build [Boost](http://boost.org/) from scratch on Ubuntu. The playbooks are tested on Ubuntu 18.04 and 20.04 for Boost 1.67.0.

Usage
-----

```sh
# On Ubuntu 18.04
ansible-playbook ./build_boost_bionic.yaml
# On Ubuntu 20.04
ansible-playbook ./build_boost_focal.yaml
```
