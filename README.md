# copy inventory file and main.yml file at root path where repo clone and run below ansible command

#for check the ping
ansible -i inventory -m ping master-node
  
#for run the role
ansible-playbook -i inventory main.yml
