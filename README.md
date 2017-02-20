# README.md
# Ansible Role: indigo-repo

An Ansible role that deploys INDIGO-DataCloud repository.

## Supported platforms

    CentOS7 & Ubuntu 14.04

## Role Variables

Available variables are listed below, along with default values:

    indigo_release: 1
    enable_openstack_distro_repo: true

## Dependencies

- geerlingguy.repo-epel - configure EPEL repository for RHEL/CentOS systems.

## Example Playbook

    - hosts: all
      roles:
        - { role: indigo-dc.indigo-repo }

## License

Apache 2.0
