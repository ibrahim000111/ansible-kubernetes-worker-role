1. create inventory file at root folder 

2. create main.yml file at root folder

---

- name: Install dockerand kubernetes master node
  hosts: kubernetes_master
  become: true
  remote_user: root

  roles:
   - anible-kubernetes-role-master 

