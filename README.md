ansible-openvpn
================
This playbook helps you deploy OpenVPN at your workstation

# Quickstart
## Requirement
- ansible > 2

## Prepare your environment configs
1. Setup global variables: `group_vars/all`
2. Writedown your vpn server ip information in the inventory file: `inventory`

## Start to deploy your OpenVPN
> ansible-playbook -i inventory -vvvv playbook.yml
