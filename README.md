ansible_reposado
================
Trying to automate installation of reposado. 
Tested on CentOS 6.5 x86_64, Ubuntu 12.04 LTS x86_64.

*The playbook.yml has hosts set to reposado make sure to change it to want you would like.
*I need to test Ubuntu a bit more, but I believe it works. 

```	
git clone https://github.com/utinajero/ansible_reposado.git 
ansible-playbook /path/to/playbook/playbook.yml --sudo
```	

On remote Host Run the below:
```
cd /usr/local/sbin/reposado/code
sudo ./repoutil --configure # the next 3 lines below are the answers that need to be entered
/var/local/reposado/html
/var/local/reposado/metadata
http://su.your.org # change this one to your FQDN
udo ./repo_sync
```	
