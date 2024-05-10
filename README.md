# arch-setup
Scripted post-setup of Arch Linux

## Steps
1. Install Ansible: `pacman -Sy ansible-core`
2. Install *community.general*: `ansible-galaxy collection install community.general`
3. Clone repo: `cd ~ && git clone https://github.com/jameskaupert/arch-setup.git && cd arch-setup/ansible`
4. Run playbook: `ansible-playbook playbook.yml`
