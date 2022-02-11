# Fedoseev

All configs and host included into repository.

Run width inventory file: `ansible-playbook playbook.yml -i hosts`

# Task list

## Stage 1:

 - [x] apt update + curl install
 - [x] Enable UFW and allow ports
 - [x] Change SSH settings
 - [ ] Create users
 - [x] Install Docker
 - [x] Run `docker-install.sh`
 - [x] Create dir /skillcloud-nginx and copy files
 - [x] Restart SSH and UFW

## Stage 2:

 - [x] Build docker
 - [x] Start docker-compose
 - [ ] Check balance