# nginx

Ansible role to install and configure Nginx http server.

## Requirements

None.

## Role Variables

Many. See defaults/main.yml

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://git.sekoya.org/mb/nginx.git roles/nginx`

## Example Playbook

    - hosts: servers
      roles:
         - nginx


    - hosts: servers
      roles:
         - { role: nginx, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
