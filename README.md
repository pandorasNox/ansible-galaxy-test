# ansible-galaxy-test

## instructions

### setup passwordless ssh
- ensure you can ssh into the server without problems

### install "external" ansible rolls
```
ansible-galaxy install -p ./ansible_vendor -r ./requirements.yml
```

### adapt inventory file
```
cp example.inventory.yml inventory.yml
```
- adapt inventory.yml

### (optional) adapt ansible.cfg
- adapt ansible.cfg

### run it
```
make setup
```
