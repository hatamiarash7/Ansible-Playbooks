# Ansible Playbooks

![logo](Ansible_logo.svg.png)

Some playbooks for Ansible

Create `env.yml` file in root :

```yml
# host name from /etc/ansible/hosts
hosts: "server_room"

# docker password or authentication key for 2FA
docker_password: "15675793e429f70"
```

### Run playbooks

```bash
ansible-playbook <directory>/<file>.yml -e @env.yml
```

Go to each directory to see description from `README.md` files
