# Ansible
  
Deploys application in !!!DEV!!! environment
Uses: https://github.com/elastic/ansible-elasticsearch

Example playbook:

```
- hosts: dev
  roles:
     - itandwidom-deploy/python_env
     - { role: itandwidom-deploy/elasticsearch, es_instance_name: "node1"
     - itandwidom-deploy/project_setup                                
     - itandwidom-deploy/project_setup
```
