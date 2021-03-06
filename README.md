# Ansible Role: domain-join

[![Build Status](https://travis-ci.org/sbaerlocher/ansible.domain-join.svg?branch=master)](https://travis-ci.org/sbaerlocher/ansible.domain-join) [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://sbaerlo.ch/licence) [![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-domain--join-blue.svg)](https://galaxy.ansible.com/sbaerlocher/domain-join)

## Description

Adds a Windows client or Server to a domain.

## Installation

```bash
ansible-galaxy install sbaerlocher.domain-join
```

## Requirements

None

## Role Variables

| Variable                   | Default | Comments (type) |
| :------------------------- | :------ | :-------------- |
| domain_join_domain_name    |         |                 |
| domain_join_admin_user     |         |                 |
| domain_join_admin_password |         |                 |
| domain_join_ou             |         |                 |

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
    - sbaerlocher.domain-join
```

## Changelog

### 1.0

- initial commit

## Author

- [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2020, Simon Bärlocher
