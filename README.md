# Freifunk Kiel -  update all VPNs

### configuration:

- `hosts`
define your hosts and usernames that have sudo rights

- `roles/dhcp/main.yml`
variables for your community

call this script with 

    ansible-playbook update-vpns.yml -v --ask-sudo-pass

## Ansible Gateway Setup for Kiel

We have a full Gateway setup at:

https://github.com/TobleMiner/freifunk-infrastructure-ansible/
