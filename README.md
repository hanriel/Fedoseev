# Fedoseev

All configs and host included into repository.

Run width inventory file: `ansible-playbook playbook.yml -i hosts`

Tasks:

 - [+] apt update + curl install
 - [+] Enable UFW and allow ports
 - [+] Change SSH settings
 - [ ] Create users
 - [+] Install Docker
 - [+] Run `docker-install.sh`
 - [ ] Create dir /skillcloud-nginx and copy files
 - [+] Restart SSH and UFW
