# ansible
Playbook diary

Here i'm going to share ansible playbooks. 

- debian-docker (going to set fresh installed server to use docker with non root user)
	* Replace in debian-docker/roles/docker/vars/main.yml your_server_ip with your server IP and server_nonroot_user with your server user name 
	* You will need ansible 2.2+ and server debian 8+
	* In the end server will restart, and you can login and play (or not) with docker engine and docker-compose
