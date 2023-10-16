# ansible-boilerplate
Ansible sample project to get started with ansible project

## Install Ansible locally

```bash
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
```

## Command to run

```bash
ansible-playbook -i hosts site.yml
```
This will install nvm & then install node 18.

## Verify results
You will observe node version 12.18.0 is installed locally.

```bash
nvm list
```

*NOTE: For now this will delegate to localhost machine, you can change hosts file to point it to your server.*

Happy Automation!
