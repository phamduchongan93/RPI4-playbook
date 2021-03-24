# RPI4-playbook

## Description
- This ansible playbook is used to acheive the following things
  - install docker engines.
  - install python enviroment.
  - essential packages for network testing. 

## Usuage
- Type the following command to run the playbook
```
  ansible-playbook -i inv rpi4-playbook.yml --ask-become
```
- Then, type in the sudo password of remote machine.

**Note**: Edit *inv* file to change the ip of the raspberry pi 4.


