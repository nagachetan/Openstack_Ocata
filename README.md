################### Installation of Openstack Ocata ########################

1. Target should be Ubuntu 16.04 OS
2. Install ansible==2.3 in management server which can connect to target servers
3. Update the inventory/host file with target controller and compute section ip details
4. Update the group_vars/all with credentials and other details
5. Update the group_vars/input_file with management interface ip details
6. Run the playbook 
