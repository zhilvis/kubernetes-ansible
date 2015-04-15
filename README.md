# Kubernetes-ansible

## Usage

Add master and minion IPs to the inventory.
Subscribe each machine to RHEL network.
Enable extras repo with:: 

    $ subscription-manager repos --enable rhel-7-server-extras-rpms 

Change ansible_ssh_user in group_vars/all.yml
Run ansible setup.yml playbook

    $ ansible-playbook -i inventory setup.yml

