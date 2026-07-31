# Ansible
A consolidated [Ansible](https://www.redhat.com/en/ansible-collaborative) repository in support of rapid reconstruction of GardenGate infrastructure.
### Dependencies:
1. [ProxmoxVE](https://www.proxmox.com/en/products/proxmox-virtual-environment/overview) root/admin account provisioned with API token access.
### Requirements:
1. Ensure `./group_vars/all.y(a)ml` has been built and contains the necessary ProxmoxVE node and API information.
2. Run Playbook `./sweetums.y(a)ml` prior to any other machines to ensure [OPNsense](https://opnsense.org/) DHCP and DNS are functional.

