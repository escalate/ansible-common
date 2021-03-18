# Ansible Role: Raspberry - Common

[![CI](https://github.com/escalate/ansible-raspberry-common/actions/workflows/ci.yml/badge.svg?event=push)](https://github.com/escalate/ansible-raspberry-common/actions/workflows/ci.yml)

An Ansible role that manages basic operating system configuration on Raspberry Pi OS.

## Install

```
$ ansible-galaxy install escalate.raspberry_common
```

## Role Variables

Please see [defaults/main.yml](https://github.com/escalate/ansible-raspberry-common/blob/master/defaults/main.yml) for a complete list of variables that can be overridden.

## Dependencies

This role relies on the following dependencies:

* Roles: None
* Collections: [collections.yml](https://github.com/escalate/ansible-raspberry-common/blob/master/collections.yml)

## Example Playbook

```
- hosts: all
  roles:
    - role: escalate.raspberry_common
      tags: common
```

## License

MIT
