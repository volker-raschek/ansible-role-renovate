# renovate

[![Ansible Role](https://img.shields.io/ansible/role/d/58986)](https://galaxy.ansible.com/volker_raschek/renovate)

With following role can be a renovate configured. Renovate runs as container
image. As container runtime must be docker installed.

Renovate will be periodically started by systemd.

## Supported distributions

- Arch Linux
- Ubuntu 20.04

## Features

- Configuring docker-compose.yml and the config.json
- Configuring systemd service and timer unit

## Configuring

In the default directory are examples how to configure renovate. Copy the
defaults into your `host_vars` or `group_vars` and adapt the examples.
