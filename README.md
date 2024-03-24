# Network-Systems-and-Administration-CA-2023-
this repository is for the networking assignment given to us. 
for that we have to deployed two Docker containers into host machine using Ansible. We have taken two Ubuntu virtual machines and configured them into a primary and secondary machine.  First, I create a user with root access on both VMs and install OpenSSH-server for communication between them. Once Ansible is set up on the primary VM and an inventory file is created, Ansible can remotely execute commands on the managed nodes and handle Docker container deployment. I then craft an Ansible playbook with tasks for deploying the Docker containers.

References: 

Python3-pip on Managed Node - https://linuxize.com/post/how-to-install-pip-on-ubuntu-22.04/

Docker installed on Managed Node - https://docs.docker.com/engine/install/ubuntu/

Youtube - [Deploy Web Application in Docker Container using Ansible](https://youtu.be/u-_uGO95xco?si=kgukamM-HGlrWLSq)
