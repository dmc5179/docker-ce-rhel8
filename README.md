# docker-ce-rhel8
Docker CE on RHEL 8

Simple playbook to install and configure Docker Community Edition on RHEL 8

Copy inventory/inventory.example to inventory/inventory

Update your version of the inventory file

Execute Playbook

```
ansible-playbook -i inventory/inventory playbooks/docker-ce-rhel8.yaml
```

