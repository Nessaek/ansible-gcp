# Create GCP Instance With Ansible

WORK IN PROGRESS

This project uses Ansible to launch a google cloud instance.

## One-time run playbook
```
ansible-playbook -i inventories/agents instance-provision.yaml --key-file "~/.ssh/mykey.pem"
```
