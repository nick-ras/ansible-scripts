# Ansible Automation Scripts

This repository contains Ansible playbooks and configurations for managing Apache installations and other system configurations.

## Project Overview

The playbooks in this repository are designed for automating server configuration and application deployment using Ansible. The repository includes:
- Installing and removing Apache on remote hosts.
- Managing configurations using an inventory file.
- Centralizing settings through an Ansible configuration file.

## Repository Structure

```plaintext
├── ansible.cfg          # Ansible configuration file
├── inventory.ini        # Inventory file defining managed hosts
├── install_apache.yml   # Playbook for installing and configuring Apache
├── remove_apache.yml    # Playbook for uninstalling Apache
├── site.yml             # Main playbook for running multiple tasks
```
# Ansible Automation Scripts

This repository contains Ansible playbooks for managing Apache installations and configurations on remote servers.

## Setup Instructions

### Prerequisites
Ensure you have:
- **Ansible** installed (`pip install ansible` or `apt install ansible`)
- **SSH access** to the remote servers
- **Python** installed on the target machines

### Configuring the Inventory
Modify `inventory.ini` to define your target servers:

```ini
[webservers]
server1.example.com
server2.example.com

