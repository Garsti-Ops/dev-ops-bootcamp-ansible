# Module-15-Ansible

This project contains different Ansible-Playbooks for deployment of an Application inside of docker containers.

### The containers can be deployed on:
- AWS with the ec2-user
- On another Cloud-Hoster which uses a standard Ubuntu-Image
- The deployment has been refactored with different Ansible-Roles for the creation of a new user and the starting of the deployed containers

### Other playbooks in this repository can:
- Automatically set up a Nexus-Server
- Deploy a node application on the target host
- Deploy into an k8s Cluster on AWS