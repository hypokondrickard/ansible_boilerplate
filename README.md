Ansible boiler plate repo for unit testing

# Setup
preferably do this in a virtual env
```
pip install -r requirements.txt
```

# Usage
running the playbook
```
ansible-playbook main.yml -i hosts.ini
```
running the tests
```
cd ansible_boilerplate/collections/ansible_collections/ddi/ipam
molecule test
```