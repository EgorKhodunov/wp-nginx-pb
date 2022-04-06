# wp-nginx-pb
Wordpress + zabbix-agent + node_exporter Ansible playbook
### Usage
1. Create vars/vault.yml using ansible-vault and add variables as in vars/example.yml
```bash
ansible-vault create vars/vault.yml
```
2. Create hosts.ini and add hosts as in example_hosts.ini
3. Change hosts in main.yml
4. Start playbook 
```bash
ansible-playbook --ask-vault-pass -u <remote_user> ./main.yml
```
