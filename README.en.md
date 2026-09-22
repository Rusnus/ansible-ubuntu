> [Русская версия](README.ru.md)

# ansible-ubuntu
Ansible role for  Ubuntu 22.04 / 24.04 servers.  
Covers SSH, firewall (ufw), fail2ban, sysctl kernel parameters, and automatic security updates.

## Requirements
- Ansible 2.12+
- Target: Ubuntu 22.04 or 24.04
- SSH access to the target server

## What it does
| Module | What gets hardened |
|---|---|
| `ssh.yml` | Disables root login, password auth, weak ciphers; adds login banner |
