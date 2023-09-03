# Ansible Role: nfs

[![Lint](https://github.com/dcjulian29/ansible-role-nfs/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-nfs/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-nfs.svg)](https://github.com/dcjulian29/ansible-role-nfs/issues)

This an Ansible role to set up and configure NFS mounts for export.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.nfs
  src: https://github.com/dcjulian29/ansible-role-nfs.git
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
