On Master:
1. sudo apt-get update
2. sudo apt-install software-properties-common
3. sudo apt-add-repository ppa:ansible/ansible
4. sudo apt update
5. sudo apt install ansible
6. ssh-keygen
7. sudo nano /etc/ansible/hosts
8. [all]
9. host-name ansible_ssh_host=public-ip of host

On Hosts:
1. sudo apt-get update
2. sudo apt-get install python3
3. sudo nano .ssh/authorized_keys

