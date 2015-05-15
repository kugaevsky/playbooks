# Ansible playbooks

Just to play around. Proof of concept

## Requirements

* Vagrant
* Ansible

## Initial setup

```shell
$ vagrant up
$ vagrant provision

```

## Wordpress setup

### Host provision

Define host in inventory.ans

First run

    ansible-playbook -i inventory.ans wordpress.yml

All further runs

    ansible-playbook -i inventory.ans wordpress.yml -b --ask-become-pass
