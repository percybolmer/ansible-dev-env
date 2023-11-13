# Ansible playbook for my dev environment

This playbook will setup my Dev environment

If you are using MacOS you need to add homebrew via ansible galaxy
```bash
ansible-galaxy collection install community.general
```

## Run
Run using 
```bash
 ansible-playbook -v -i inventory.yml bootstrap.yml --ask-become-pass
``` 
