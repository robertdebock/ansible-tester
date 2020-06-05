# Test Ansible on VM's

Molecule is really great and when developing roles, it's nice to have a full VM to see what a roles does to a system.

This repository can be used to quickly start a VM, run a playbook against it and login to troubleshoot.

```
vagrant up
ansible-playbook some_playbook.yml
vagrant ssh 
vagrant destoy
```
