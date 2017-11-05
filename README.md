# ansible_deployment
Variable Definitions:  
deploy1 => BLUE Side App server  
deploy2 => GREEN Side App server  
webservers => Ansible group having list of APACHE webservers  
nagios => Nagios server HOSTNAME  
nagios_srv => Service name of nagios monitoring the application server  
war_src => patch of source war file to be deployed  
war_dst => destination path on tomcat server  
  
ansible-playbook deploy.yml
