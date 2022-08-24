# Install Httpd Server (Ansible Playbook)

This is a demo, how to configure management server using Ansible Playbook. In this demo, i'm try to install Httpd/Apache2 on my local Server.

> Requirement:
>
> 1. VirtualBox 
> 2. CentOS Stream 8 (Server)
> 3. Ansible
> 4. Httpd

## How to Run 
1. All the servers must connect to each other, you can settings on VM network settings. You can see on **inventory** files, there are some IP Address of my servers.

2. Run the **httpd-playbook.yaml** using this command:
   ```bash
   $ ansible-playbook -i inventory httpd-playbook.yaml

3. Try to access the website. If failed, you can check the logs on your server. 