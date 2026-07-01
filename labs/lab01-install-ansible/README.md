# Lab 01 - Install Ansible

## Objective

Install and verify Ansible Core on the control node.

## Environment

| Item | Value |
|------|-------|
| OS | Rocky Linux 9 |
| Control Node | controlnode |
| User | elliot |

## Prerequisites

- Rocky Linux 9 Minimal
- Internet access
- sudo privileges

## Steps

1. Update the system
2. Install ansible-core
3. Verify installation

## Verification

```bash
ansible --version
```

Expected output:

```text
ansible [core 2.16.16]
  config file = /etc/ansible/ansible.cfg
```
## Troubleshooting

| Problem | Solution |
|---------|----------|
| ansible: command not found | Install ansible-core package |
| Permission denied | Use sudo or check user permissions |





## References

- Red Hat Enterprise Linux Documentation
- Ansible Documentation
