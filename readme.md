# proxmox-ansible

Ansible playbooks to manage proxmox in a variety of ways

## Requirements

1. Linux (or WSL) or Mac
1. Python 3

## Getting Started

1. Clone this repository: `git clone https://c0de.dev/c0de/proxmox-ansible`
1. Enter this repository: `cd proxmox-ansible`
1. Create a Python virtual environment: `python3 -m venv .venv`
1. Activate the virtual environment: `source .venv/bin/activate`
1. (Optional) Upgrade pip: `pip3 install --upgrade pip`
1. Install requirements: `pip3 install -r requirements.txt`
1. Install Ansible General Community Collection: `ansible-galaxy collection install community.general`
    - _Note: This might already be installed._

## Running Playbooks

1. Enter the playbook directory: `cd playbooks`
1. Run `./play.sh <playbook-name>.yml`
    - The script will record a log of the output, as well as timing information in [logs](./logs)
