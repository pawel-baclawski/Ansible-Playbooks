# Ansible-Playbooks
Those Ansible playbooks can be used for fast and simple remote environments configuration.

Usage:
```
ansible-playbook PLAYBOOK -i 'HOST_ADDR ,' -u USERNAME --ask-pass --ask-become-pass
```
* PLAYBOOK - yaml file to be used
* USERNAME - user with sudo privilages which will be used to connect to remote machine and perform tasks
* HOST_ADDR - address of the remote machine

NOTE: --ask-pass and --ask-become-pass are only needed if your public key was not added to remote authorized_keys file
