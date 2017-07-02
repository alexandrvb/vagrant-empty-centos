# Vagrant with ansible provision
## Requirements
* ansible
* vagrant
## Running
Before running `vagrant up` download all ansible-roles:
```
ansible-galaxy install --roles-path roles -r requirements.yml
vagrant up
ansible-playbook vm.yml
```
