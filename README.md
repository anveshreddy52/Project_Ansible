# Project_Ansible

In this repo you will come to know how to create a sample playbook in yml language.
In roles concept, comparing in default and vars the vars will have highest priority and when compared the default, vars and command line, the cli will have the highest priority.
project flow:
1.Launch an AWS instance in my case it is ubuntu 22.04 LTS
2.Become a root user
3.Install the ansible repository and the command is below
apt-add-repository ppa:ansible/ansible
4.update the package by apt update -y
5. Now install the Ansible package by the following command below:
apt install ansible
6.vi /etc/ansible/hosts
7.later add the remote hosts ips or domain name under the groupname where you want manage the remote systems
8.try to ping to the remote systems group with ansible -m ping groupname
9.
