## Collection of Ansible Playbooks to work with my clients project


### Usage

```
ansible-playbook  -i /etc/ansible/production \
                  -v hosts_management/hosts_management.yml \
                  --limit do
```

```
ansible-playbook  -i /etc/ansible/production \
                  -vvvv containers_management/containers_management.yml \
                  --limit do
```


```
ansible-playbook  -i /etc/ansible/production \
                  -vvvv applications_management/applications_management.yml \
                  --limit do

```
