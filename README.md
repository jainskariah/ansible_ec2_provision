# ansible_ec2_provision

This code is used to setup and ec2 instance using ansible delpoyment.

This script will create an ec2 Instace,a new pem key for access the instance, cretae a security Group.

Tag the instance with a name we mention

To check the syntax of Ansible script:

ansible-playbook --syntax-check provision.yml

To run a dry run- to check what all changes are actully going to happen when the script is executed.

ansible-playbook provision.yml --check

Note:
This command wont provision ec2 instance but help us to get an idea what will happen when the command is actully executed.

To run the provision:
ansible-playbook provision.yml
