#Ansible script install [nextcloud server](https://nextcloud.com/ "nextcloud server")

Tested on Ubuntu 22.04.3 LTS

Installation:

- Run:

        ansible-galaxy install geerlingguy.nginx geerlingguy.certbot geerlingguy.docker  --force
        ansible-playbook -D nextcloud.yml -i inventory --ask-vault-password
