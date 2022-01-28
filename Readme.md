# ansible_azure
Ansible scripts for Azure testing

## Scripts
### install_azure-cli_vshell.yaml
```sh
ansible-playbook install_azure-cli_vshell.yaml
```
### install_azure-cli_vpackage.yaml
```sh
ansible-playbook install_azure-cli_vpackage.yaml -e "ansible_become_password=PASSWORD"
```
