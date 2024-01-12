# nephelaiio.postgresql_repo

[![Build Status](https://github.com/nephelaiio/ansible-role-postgresql_repo/actions/workflows/molecule.yml/badge.svg)](https://github.com/nephelaiio/ansible-role-postgresql_repo/actions/wofklows/molecule.yml)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-nephelaiio.postgresql_repo.vim-blue.svg)](https://galaxy.ansible.com/nephelaiio/postgresql_repo/)

<!--
[![Ansible Galaxy](https://img.shields.io/badge/dynamic/json?color=blueviolet&label=nephelaiio/postgresql_repo&query=%24.summary_fields.versions%5B0%5D.name&url=https%3A%2F%2Fgalaxy.ansible.com%2Fapi%2Fv1%2Froles%2F<galaxy_id>%2F%3Fformat%3Djson)](https://galaxy.ansible.com/nephelaiio/postgresql_repo/)
 -->

An [ansible role](https://galaxy.ansible.com/nephelaiio/postgresql_repo) to install and configure postgresql_repo

## Role Variables

Please refer to the [defaults file](/defaults/main.yml) for an up to date list of input parameters.

## Dependencies

By default this role does not depend on any external roles. If any such dependency is required please [add them](/meta/main.yml) according to [the documentation](http://docs.ansible.com/ansible/playbooks_roles.html#role-dependencies)

## Example Playbook

- hosts: servers
  roles:
     - role: nephelaiio.postgresql_repo

## Testing

Please make sure your environment has [docker](https://www.docker.com) installed in order to run role validation tests. Additional python dependencies are listed in the [requirements file](https://github.com/nephelaiio/ansible-role-requirements/blob/master/requirements.txt)

Role is tested against the following distributions (docker images):

  * Ubuntu Focal
  * Ubuntu Jammy
  * Debian Buster
  * Centos 8

You can test the role directly from sources using command ` molecule test `

## License

This project is licensed under the terms of the [MIT License](/LICENSE)
