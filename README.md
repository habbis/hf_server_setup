# setup standard config for server on habbfarm

variables is are encrypted with ansible-vault

To encrypt variables
```
ansible-vault encrypt defaults/main.yml
```

To edit file 
```
ansible-vault edit defaults/main.yml

```
To run playbook with vault
```
ansible-playbook site.yml --ask-vault-pass
```
