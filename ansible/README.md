# Ansible Playbooks

## prereqs
Linux, macOS, Windows
ansible (tested 2.2.1.0, 2.3.0.0)

## verify.yml
This will verify that java, javac, and maven are installed and of the necessary version.

`ansible-playbook -i "localhost," verify_prereq.yml`