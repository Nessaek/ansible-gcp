# Create GCP Instance With Ansible

## One-time run playbook

Create an instance:
```
ansible-playbook -i inventories/ instance-provision.yaml --key-file "~/.ssh/mykey"
```
Terminate an instance:
```
ansible-playbook -i inventories/ instance-termination.yaml --key-file "~/.ssh/mykey"
```