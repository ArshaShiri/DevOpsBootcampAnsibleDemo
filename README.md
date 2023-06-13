# DevOps Bootcamp Ansible Demo

`my-playbook.yaml` contains a simple config where the servers under `webserver` group are targeted and nginx is installed on them. `ansible.cfg` contains the configuration for ansible for this project. To execute ansible playbook:

    ansible-playbook -i hosts my-playbook.yaml