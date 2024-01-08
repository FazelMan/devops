# Install Ansible First

```
apt update && apt install python3-pip
python3 -m pip install --user ansible
python3 -m pip install --user ansible-core
python3 -m pip install ansible
```

# And run it
```
ansible-playbook -i hosts ansible.yml
```

==============================================================================

# If run on localhost
add `connection: local` to `ansible.yml` and change hosts to `localhost`
```
hosts: localhost
connection: local
```

## And run it
```
ansible-playbook ansible.yml
```
