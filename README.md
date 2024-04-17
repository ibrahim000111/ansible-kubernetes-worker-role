# copy inventory file and main.yml file at root path where repo clone and run below ansible command

ansible -i inventory -m ping master-node
  
ansible-playbook -i inventory main.yml
