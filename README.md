ansible_reposado
================
Tested on CentOS 6.5 x86_64. Will work on setting it up to also support Ubuntu.

Trying to automate installation of reposado. 
The playbook.yml has hosts set to all make sure to change to want you would like or remove it.

	git clone https://github.com/utinajero/ansible_reposado.git 
	ansible-playbook /path/to/playbook/playbook.yml --sudo
	cd /usr/local/sbin/reposado/code
	sudo ./repoutil --configure # the next 3 lines below are the answers that need to be entered
	/var/local/reposado/html
	/var/local/reposado/metadata
	http://su.your.org # change this one to your FQDN
	sudo ./repo_sync
  	
