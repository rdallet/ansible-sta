# Ansible

## Inventory

`development/hosts`

## Use

### Dependencies installation

```
ansible-galaxy install -r requirements.yml
```

### Run playbooks
#### Dry mode

```
ansible-playbook playbook_sta.yml --check
```

#### Real mode

```
ansible-playbook playbook_sta.yml
```

