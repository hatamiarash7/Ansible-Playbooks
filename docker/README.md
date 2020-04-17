# Docker playbooks

Deploy Docker by Ansible ( with docker-compose )

### Install docker

```bash
ansible-playbook docker/install.yml -e @env.yml
```

### Check installed docker

```bash
ansible-playbook docker/info.yml -e @env.yml
```

### Login into Docker Hub

First you need to set `docker_password` var in `env.yml` ( normal password or authentication key for 2FA ) and :

```bash
ansible-playbook docker/login.yml -e @env.yml
```
