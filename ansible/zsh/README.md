# Install Ansible First

```
apt update && apt install python3-pip
python3 -m pip install --user ansible
python3 -m pip install --user ansible-core
python3 -m pip install ansible
```

# How to run?
```
ansible-playbook -i hosts zsh-and-ohmyzsh.yml
```
