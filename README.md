# Ansible Node Deployment

Automates deployment of Node.js applications using Ansible.

## Servers

| Server | IP | Port |
|--------|-----|------|
| server1 | 20.235.192.53 | 22 |
| server2 | 192.168.1.100 | 2222 |
| server3 | 192.168.1.100 | 2223 |

## Security Note

> **Do NOT commit plain-text passwords.**
> Use one of the following instead:
>
> - **Ansible Vault** to encrypt sensitive vars:
>   ```bash
>   ansible-vault encrypt_string 'your_password' --name 'ansible_password'
>   ```
> - **SSH keys** for authentication (recommended):
>   ```bash
>   ssh-copy-id -i ~/.ssh/id_rsa.pub legendaryappuser@20.235.192.53
>   ```
