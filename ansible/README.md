## Ansible Module for installation Elasticsearch
​ 
#### Prerequisite

- ansible 2.9 
- vim

### 1.) Create Directory for Elasticsearch 
```shell 
mkdir -p /data/ansible/elasticsearch/source/
cd /data/ansible/elasticsearch
vi install-elasticsearch-7-8-0.yaml
vi inventory
```
### 2.) Run Ansible Playbook  
```shell 
ansible-playbook -i inventory install-elasticsearch-7-8-0.yaml
