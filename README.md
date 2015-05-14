Ansible
=======

My Ansible Playbooks and Dependencies

Currently just a work in progress. Soon will be able to spin up my default Ubuntu workstation from clean install to fully operational.

How To Run
----------
@ Create your ssh key first and replace it with  id_rsa.pub

From the root directory:
`ansible-playbook -i hosts playbooks/bootstrap.yml -f 10 -K`

You will be prompted to enter your root password.
