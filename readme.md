# Not complete nginx part is not working correctly

- all sources are mentioned in files
- how to run it?
1. Install dependencies 
```
ansible-galaxy install -r requirements.yml
```
2. run playbook with inventory
```
ansible-playbook setup.yml -i inventory.txt
```

Server config it was tested: ansible 2.8.3 and Ubuntu 18.04.3 LTS

Server HW:
```
1 vCPU

1 GB RAM

20 GB SSD
```