## Ansible Module for installation Elasticsearch
​ 
#### Prerequisite

- ansible 2.9 
### 1.) Create Directory for Elasticsearch 
```shell 
mkdir -p /ansible/elasticsearch/source/
cd /ansible/elasticsearch
vi install-elasticsearch.yaml
vi inventory
```
### 2.) Run Ansible Playbook  
```shell 
ansible-playbook -i inventory install-elasticsearch.yaml
