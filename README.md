# Freifunk Kiel -  update all VPNs

###configuration:

- `hosts`
define your hosts and usernames that have sudo rights

- `roles/dhcp/main.yml`
variables for your community

call this script with 

    ansible-playbook update-vpns.yml -v --ask-sudo-pass
