# Ansible: configurable Nginx site

## Files
- playbook.yml
- templates/index.html.j2
- templates/nginx-site.conf.j2
- inventory.ini

## Vars
- app_name
- root_dir
- nginx_port

## Run
ansible-playbook -i inventory.ini playbook.yml -K
