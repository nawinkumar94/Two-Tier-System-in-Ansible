# Two-Tier-System-in-Ansible
Installing all the required packages in basic two tier system

---> Two Tier System with Single load balancers and multiple Webservers

# Update all the yum packages for webservers and loadbalancers ("yum-update.yml")

# Install all thes services apache and php for webservers and load balancers ("install-services.yml")
  
# To setup our webservers and configure it ("setup-app.yml")
  
# To setup our load balancers and configure it ("setup-lb.yml")
  
# Check the status of the apache ("check-status.yml")

# Host file with webservers ip and load balancers ip ("hosts-dev")

# CFG file with configuration ("ansible.cfg")

# php file ("index.php")

# Config file with jinja2 to load all the webservers dynamically for load balancers (lb-config.j2)
