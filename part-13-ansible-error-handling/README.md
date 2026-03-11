## Run playbook

```bash
ansible-playbook --inventory inventory/ansible-error-handling-playbook/hosts ansible-error-handling-playbook.yml
```

## ignore-errors = ignores errors and finish the playbook
## failed-when = you give the condition when something is error
## block , rescue , always = block main part of the playbook , rescue when smt wrong
## always = always does the task
## any-error-fatals = one mistake , then stop everything
## 
