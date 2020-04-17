# Redis

Install and create a redis service

### Install redis

```bash
ansible-playbook redis/install.yml -e @env.yml
```

### Uninstall redis

```bash
ansible-playbook redis/uninstall.yml -e @env.yml
```
