This repository contains [Ansible][] playbooks to set up my desktop machines.
These playbooks assume you are running Arch Linux.

[Ansible]: http://ansible.com

## Dependencies

In addition to the base `ansible` package, you also need `python2-passlib` to
generate the password at the password prompt.

## Usage

    ansible-playbook -i localhost, setup.yml
