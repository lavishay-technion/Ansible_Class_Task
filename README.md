## Ansible Task

### Main objective

- "reados.sh" bash script determines Linux Distro based on os-release file in `/etc` folder
- RunScripts.yaml is a playbook that copies the script to all servers in inventory file
- Using Ansible to run the script on all the servers in the inventory file

### Pre-requisitions
- Ansible installed


##### Configuration on these files match "Ansible_Shallow" docker env. 