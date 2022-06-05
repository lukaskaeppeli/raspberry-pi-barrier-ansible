# raspberry-pi-barrier-ansible

command for clients:
barrierc -f --disable-crypto "ENTER_SERVER_ADDRESS_HERE!"

# Automated barrier setup on Raspberry pi

This repository takes the steps from this [Repository](https://github.com/similicious/barrier-headless) and automates the steps with ansible.

# Setup
1. Install [Ansible](https://www.ansible.com/) 
```bash
sudo apt install ansible
```

2. Create hosts file according to the template hosts.tmp

3. Run the playbook
```bash
ansible-playbook -i hosts site.yml
```
