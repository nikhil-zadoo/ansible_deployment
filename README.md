# ansible_deployment
Variable Definitions:
deploy1 => BLUE Side App server
deploy2 => GREEN Side App server
deploy => deploy1 + deploy2
webservers => Ansible group having list of APACHE webservers
nagios => Nagios server HOSTNAME
nagios_srv => Service name of nagios monitoring the application server
