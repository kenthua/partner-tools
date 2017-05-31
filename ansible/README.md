# Ansible Playbooks

## prereqs
ansible

## verify.yml
This will verify that java, javac, and maven are installed and of the necessary version.

`ansible-playbook -i "localhost," verify_prereq.yml`