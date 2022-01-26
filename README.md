# My-Ansible-Installation
This is the step by step of my Ansible installation in my personal infrastructure

I am using Ubuntu Server and it's installed on VM Esxi machine.

The first thing i do is execute a update:
$ sudo apt update

And then execute the following commands in this specific order:

$ sudo apt install software-properties-common
$ sudo add-apt-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible
