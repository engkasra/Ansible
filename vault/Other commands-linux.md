```bash
ansible-vault encrypt_string --vault-id your-user@prompt 'testpassword' --name 'ansible_password'
ansible-playbook -i inventory/hosts --vault-id your-user@prompt backup.yaml
```
