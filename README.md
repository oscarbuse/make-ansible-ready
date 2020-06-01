## Role: make-ansible-ready
* Create ansible users who can deploy later with sudo and no password.

### Example usage: 
	ansible-playbook -i hosts.inv -u vagrant -l "fqdn" make-ansible-ready.yml
