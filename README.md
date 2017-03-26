## Ansible Playbook example with multiple docker container 

## Requirements

* docker 1.11+
* ansible v2+


## Build and run docker container

   1. git clone https://github.com/vedata/ansible-apache.git
   2. cd ansible-apache
   3. docker build -t ssh-host01 .
   4. docker run --name dhost01 -it ${IMAGE}


## Run ansible playbook

   1. ansible-playbook apache.yml --ask-sudo-pass
