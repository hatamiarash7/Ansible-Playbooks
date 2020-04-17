# Network Playbooks

some playbooks to configure your network

### Set DNS ( using netplan )

Set your addresses in `netplan_dns.yml` and :

```bash
ansible-galaxy install kwoodson.yedit
ansible-playbook network/netplan_dns.yml -e @env.yml
```
