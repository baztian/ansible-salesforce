# Ansible role to install salesforce tools

[![CI](https://github.com/baztian/ansible-salesforce/workflows/CI/badge.svg)](https://github.com/baztian/ansible-salesforce/actions/workflows/main.yml)

Role to download, install and setup salesforce tools mainly for development purposes.

Npm needs to be installed. You can do so via [baztian.js](https://galaxy.ansible.com/baztian/js) role.

## Example Playbook

    - hosts: servers
      become: yes
      roles:
         - role: baztian.js
         - role: baztian.salesforce

## License

MIT
