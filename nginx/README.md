# Nginx playbooks

Deploy Nginx by Ansible

`index.html` is a simple HTML file for test

### Install Nginx

```bash
ansible-playbook nginx/install.yml -e @env.yml
```

### Uninstall Nginx

```bash
ansible-playbook nginx/uninstall.yml -e @env.yml
```
