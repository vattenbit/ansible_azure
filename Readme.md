# ansible_azure
Ansible Playbooks/Roles for Azure

## Environment Configuration

### Install and Configure Virtualenv
We need install virtualenv and generate a venv with requirements.txt

```
pip3 install virtualenv
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt
```

### Ansible Collections Requeriments
```
ansible-galaxy collection install azure.azcollection
```

### Environment Variables
```
export AZURE_CLIENT_ID=***
export AZURE_SECRET=***
export AZURE_SUBSCRIPTION_ID=***
export AZURE_TENANT=***
```