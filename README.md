# ansible-drupal
Ansible playbook for Drupal installation on centos.
Installs Drupal, an open source content management platform, on Redhat/Centos.

# Dependency
. Ansible

Before you run the Playbook, your ~/.ssh/known_hosts file should have an entry for each of the hosts mentioned in the hosts file.

# Inventory / host file 
 Define hosts / group of hosts to be affected in inventory / host file.
 
# Set Up Drupal
Drupal Setup Page

Your database settings will be the variables you set in the vars section of the drupal/site.yml file.
Now complete the browser-based installation, at http://your_server_ip/drupal/.

# Run Playbook

o run:
       cd ~/drupal/
       ansible-playbook -i hosts site.yml
        

