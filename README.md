ansible_reposado
================

Trying to automate installation of reposado. 

	git clone https://github.com/utinajero/ansible_reposado.git 
	ansible-playbook /path/to/playbook/playbook.yml --sudo
	cd /usr/local/sbin/reposado/code
	sudo ./repoutil --configure # the next 3 lines below are the answers that need to be entered
	/var/local/reposado/html
	/var/local/reposado/metadata
	http://su.your.org # change this one to your FQDN
	sudo ./repo_sync # starts the sync
  	
