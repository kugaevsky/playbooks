# Ansible playbooks

Just to play around

## Requirements

* Vagrant
* Ansible

## Run

```
$ vagrant box add ubuntu/trusty64
$ vagrant up
# echo '192.168.33.44 ansible.vagrant.local' >> /etc/hosts 
$ ansible-playbook initial.yml -i inventory.ans -s

```