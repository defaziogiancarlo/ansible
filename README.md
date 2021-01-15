# ansible
Ansible playbooks for ansible-pull and for local vms

## Prereqs
have git and ansible installed, have internet connection

## usage
from the computer you want to set up
this will execute the playbook local.yml
sudo ansible-pull -i $(uname -n), -U https://github.com/defaziogiancarlo/ansible.git
