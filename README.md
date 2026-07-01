# Ansible Automation Project

Ansible playbooks for automating server configuration and deployment.

## Project Structure
ansible-project/
├── roles/
├── inventory/
├── ansible.cfg
├── site.yml
├── apache.yml
├── first_playbook.yml
├── loops_test.yml
├── vault_test.yml
└── secret.yml

## Tech Stack
- Ansible
- AWS EC2
- Apache
- Ansible Vault

## What This Does
- Server configuration automation
- Apache web server deployment
- Ansible roles management
- Secret management with Ansible Vault
- CI/CD with GitHub Actions

## How to Run
ansible-playbook -i inventory site.yml

## What I Learned
- Ansible playbooks and roles
- Inventory management
- Ansible Vault for secrets
- GitHub Actions CI/CD pipeline
- Remote server automation
