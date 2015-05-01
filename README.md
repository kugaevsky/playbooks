# Ansible playbooks

Just to play around

## Requirements

* Vagrant
* Ansible

## Run

```
$ vagrant box add ubuntu/trusty64
$ vagrant up
# echo 'ansible.vagrant.local 192.168.33.44' > /etc/hosts 
$ ansible-playbook initial.yml -i inventory.ans -s
