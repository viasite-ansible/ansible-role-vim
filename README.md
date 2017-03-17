[![Build Status](https://travis-ci.org/viasite-ansible/ansible-role-vim.svg?branch=master)](https://travis-ci.org/viasite-ansible/ansible-role-vim)

Installs https://github.com/viasite/vim-config

## Example playbook

You can define public keys via files or via variables:
``` yaml
- hosts: all
  remote_user: root
  vars:
    vim_packages: [ vim-gtk ]
    vim_user: testuser
  roles:
    - vim
```
