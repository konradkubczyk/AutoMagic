# AutoMagic

## About this project

The repository contains an Ansible playbook that will install required software and configure my personal computer. It is designed to be run on a fresh install of [Fedora Linux 39 (Workstation Edition)](https://fedoraproject.org/) and on **specific devices only**.

## Usage

To execute the playbook using a single command, run the following (any `playbook.yml` file will be overwritten, if it already exists in the current directory):

```bash
git clone https://gitlab.com/konradkubczyk/automagic.git && cd automagic && sudo dnf -y install ansible && sudo ansible-playbook playbook.yml && cd .. && rm -rf automagic
```

> After the playbook finishes, please reboot your computer or log out and log back in.
