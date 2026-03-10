## Run playbook

```bash
ansible-playbook --inventory inventory/ansible-deployment-strategy/hosts ansible-deployment-strategy.yml
```


## Limit on sub-set of server

```bash
ansible-playbook --inventory inventory/ansible-deployment-strategy/hosts ansible-deployment-strategy.yml --limit blue 
```

