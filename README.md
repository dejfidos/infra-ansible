#infra-ansible

Ansible lab project:
- inventories
- common role baseline (packages, timezone)
- Ubuntu Server VMs (NAT + Host-Only)

How to run:
ansible-playbook -i inventories/dev/hosts.ini playbooks/site.yml
