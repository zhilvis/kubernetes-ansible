# Kubernetes-ansible

## Usage

1. Add master and minion IPs to the inventory.

2. Subscribe each machine to RHEL network.

3. Enable extras repo with:

    $ subscription-manager repos --enable rhel-7-server-extras-rpms 

4. Change ansible_ssh_user in group_vars/all.yml

5. Run ansible setup.yml playbook

    $ ansible-playbook -i inventory setup.yml

