## Ansible role to install wallabag in a docker container

It installs a docker container that runs wallabag, one with a redis db and one with a pocket import worker.
The containers are managed by systemd.

To configure, override the defaut variables in `defaults/main.yml`.
