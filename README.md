# Ansible
My adventures into Ansible and YAML

Important note: If you are like me, you may be following the Ansible Documentation or other guide. IF YOU TRY TO USE THE REBOOT AD-HOC COMMAND, IT WILL GIVE AN ERROR! 
That is ok apparently. I got stuck thinking something was wrong with my setup. Then I decided to have a shell open to the remote server when running the reboot ad-hoc
command and saw the connection reset. 

I recommend using a playbook to add a user or something simple to test your setup and SSH connections. See my dex.yml
