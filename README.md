ansible_reposado
================

Trying to automate installation of reposado. 

	ansible-playbook /path/to/playbook/playbook.yml --sudo
	cd /usr/local/sbin/reposado/code
	sudo ./repoutil --configure # the next 3 lines below are the answers that need to be entered
	/var/local/reposado/html
	/var/local/reposado/metadata
	http://su.your.org
	sudo ./repo_sync # starts the sync
  	
