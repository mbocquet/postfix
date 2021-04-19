# postfix

Ansible role to install and configure postfix.

## Requirements

None.

## Role Variables

See defaults/main.yml for details

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://git.sekoya.org/mb/postfix.git roles/postfix`

## Example Playbook

    - hosts: servers
      roles:
         - postfix


    - hosts: servers
      roles:
         - { role: postfix, x: 42 }


    - hosts: servers
      roles:
         - role: postfix
           x: 42

## License

GPLv3

## Author Information

http://www.sekoya.org
