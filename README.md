# setup
```
hosts file:  /etc/ansible/hosts
config file:  /etc/ansible/ansible.cfg
```
# adhoc commands
```
ansible -i /etc/ansible/hosts all -m ping
```
# setup ssn key connection
```
To add a host to /etc/ansible/hosts with a specific ssh key and user:
44.202.111.133 ansible_ssh_private_key_file=/home/ubuntu/.ssh/id_rsa ansible_user=ubuntu

https://docs.ansible.com/ansible/latest/user_guide/connection_details.html
```
