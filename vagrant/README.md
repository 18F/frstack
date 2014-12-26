# vagrant single host configuration 

This configuration installs all ForgeRock products on a single vagrant host. This is suitable for development where HA is not required. 


## Usage 

vagrant up|Creates VM and runs ansible provisioning.
vagrant provision| Re-run vagrant provisioning 
./frstack [tags]|Run ansibe playbook manually. You can optional suppply a comma seperated list of tags - which will run only those tasks with the given tag.


vagrant ssh   -  ssh into the guest 

The guest will be provisioned with a host only IP of 192.168.56.11. Add an entry to your /etc/hosts file, and then bring up a web browser to http://openam.example.com 


