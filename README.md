# Assignment
1) Provisioned two t2.micro EC2 instances with Ubuntu Server 16.04 LTS operating system 
2) Required tools (NVM, Node, Docker, Docker Compose, OpenSSL, Git) using Ansible. You can find this file on path: Assignment/etc/ansible/playbook1.yaml
3) Apache web server installed using Docker compose file Assignment/etc/ansible/docker-compose.yaml and deployment configured using Ansible playbook named playbook-apache.yaml
4) CoughDB installed using Docker compose file Assignment/etc/ansible/docker-compose.yml and deployment configured using Ansible playbook named playbook-coughdb.yml

# Code Execution Steps:
1) Provision servers and name accordingly. 
2) Install Ansible and configure Hostfile and set Hostname
3) Use playbook Assignment/etc/ansible/playbook1.yaml to install required tools
4) Use Docker Compose file on the path Assignment/etc/ansible/docker-compose.yaml to install apache web server
5) Use Playbook playbook-apache.yaml for deployment
6) Perform step 5 and step 6 for CoughDB (use Assignment/etc/ansible/docker-compose.yml and playbook-coughdb.yml here)
