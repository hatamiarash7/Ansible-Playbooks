# Kubernetes

Create Kubernetes cluster using Ansible

### Configure

Check `hosts` and change your `/etc/ansible/hosts` like this

### Install dependencies

```bash
ansible-playbook kubernetes/dependencies.yml --extra-vars "hosts=all"
```

### Configure nodes

```bash
ansible-playbook kubernetes/master.yml
ansible-playbook kubernetes/workers.yml
```
