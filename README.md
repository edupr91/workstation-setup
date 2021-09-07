# Workstation setup
Documentation work in progress

First run pre-setup.sh 

```
ansible-galaxy collection install community.general
```

```
# Dry-run
$ ansible-playbook  -i hosts setup.yaml  -K  -C 
# Apply changes
$ ansible-playbook  -i hosts setup.yaml  -K  
``
