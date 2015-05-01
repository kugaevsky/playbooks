# Ansible playbooks

Just to play around

## Requirements

* Vagrant
* Ansible

## Initial setup

```shell
$ vagrant up
$ vagrant provision

```

## Wordpress procisioning

```
$ ansible-playbook -i inventory.ans wordpress.yml -s --ask-sudo-pas
```
