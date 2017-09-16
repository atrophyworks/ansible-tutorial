## Install Varnish Cache
1. download and put this folder
1. cd this folder
1. edit inventory/group_vars/all.yml according to the varnish version you use 
1. `ansible-playbook -i inventory/dev plays/deploy/cache.yml`