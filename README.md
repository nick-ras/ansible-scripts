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
