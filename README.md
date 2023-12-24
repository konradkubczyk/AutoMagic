# AutoMagic

## About this project

The repository contains an Ansible playbook that will install required software and configure my personal computer. It is designed to be run on a fresh install of [Fedora Linux 39 (Workstation Edition)](https://fedoraproject.org/).

## Quick start

To execute the playbook using a single command, run the following (any `playbook.yml` file will be overwritten, if it already exists in the current directory):

```bash
wget https://gitlab.com/konradkubczyk/automagic/-/raw/main/playbook.yml --output-document=playbook.yml && sudo dnf install ansible -y && ansible-playbook playbook.yml
```
