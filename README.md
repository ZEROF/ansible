# ansible
Playbook diary

Here i'm going to share ansible playbooks. 

- debian-docker (going to set fresh installed server to use docker with non root user)
	* Replace in debian-docker/roles/docker/vars/main.yml your_server_ip with your server IP and server_nonroot_user with your server user name 
	* You will need ansible 2.2+ and server debian 8+
	* In the end server will restart, and you can login and play (or not) with docker engine and docker-compose

- gcloud-sdk is small role i wrote for debian 8, if you are using Google Cloud you will need this SDK for better workflow
	* Just replace host and user settings in playbook to fit your needs
