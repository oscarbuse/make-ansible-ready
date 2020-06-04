## Role: make-ansible-ready
Just for demonstration purpose as part of repo "learning-ansible"
* Create ansible user ("harry" ) who can deploy later with sudo and no password.

### Example usage: 
	ansible-playbook -i hosts.inv -u vagrant -l "fqdn" make-ansible-ready.yml
