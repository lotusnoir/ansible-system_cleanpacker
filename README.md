# ansible-system_cleanpacker

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_cleanpacker-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_cleanpacker)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_cleanpacker.svg)](https://github.com/lotusnoir/ansible-system_cleanpacker/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_cleanpacker?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/system_cleanpacker)
[![downloads](https://img.shields.io/ansible/role/d/56915)](https://galaxy.ansible.com/lotusnoir/system_cleanpacker)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56915)](https://galaxy.ansible.com/lotusnoir/system_cleanpacker)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Cleanning tasks before finalise packer image

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: system_cleanpacker
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-system_cleanpacker


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

