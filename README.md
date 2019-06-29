#Ansible script install [nextcloud server](https://nextcloud.com/ "nextcloud server")

Tested ubuntu 18.04

Installation:

- Edit inventory_example file.
- Run:

        ansible-galaxy install geerlingguy.nginx geerlingguy.certbot geerlingguy.docker
        ansible-playbook -D nextcloud.yml -i inventory_example
