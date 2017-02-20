# README.md
# Ansible Role: indigo-repo

An Ansible role that deploys INDIGO-DataCloud repository.

## Supported platforms

    CentOS7 & Ubuntu 14.04

## Role Variables

Available variables are listed below, along with default values:

    indigo_release: 1

## Dependencies

- geerlingguy.repo-epel - configure EPEL repository for RHEL/CentOS systems.

## Example Playbook

    - hosts: servers
      roles:
        - { role: indigo-repo }

## License

Apache 2.0
