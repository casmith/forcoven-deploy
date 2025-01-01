# Forcoven Deployment

This repository contains infrastructure-as-code files for forcoven.com. It uses ansible and docker-compose to automate deployment of the website. 

## Manual Deployment

For now, deployment is done manually on a host machine. SSH needs to be configured to allow key-based authentication to the target machine. Once that is configured, simply run the following command to deploy: 

`ansible-playbook -i hosts.yaml ansible.yaml`
