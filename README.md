# Kubernetes-ansible

## Usage

1. Add master and minion IPs to the inventory.

2. Subscribe each machine to RHEL network.

3. Change ansible_ssh_user in group_vars/all.yml

4. Run ansible setup.yml playbook

    $ ansible-playbook -i inventory setup.yml

