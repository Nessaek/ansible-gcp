# Deploy to GCP Kubernetes using Ansible

## One-time run playbook
Install all the dependecies in a remote machine which will deploy to Kubernetes
```
ansible-playbook -i inventories/agents enable-machine-to-deploy-to-k8s.yaml --key-file "~/.ssh/mykey.pem"
```

## From the agent above
Run this playbook to deploy a "Hello World" type of container
```
ansible-playbook -i inventories/tutum tutum-deploy
```
