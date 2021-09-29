# Icinga-installation-using-ansibleplaybook-in-Centos8

#install Ansible in Local machine

#Open Browser and use the url http://localhost/icingaweb2/setup

.............................................................

#use the command for view token for icingaweb2 

icingacli setup show token

..............................................................

#check the Creds below during installation...

DB1 name: icingaweb2

passwd:icingaweb2

..................

DB2 name: icinga2

passwd: icinga2

...................

api_user name: root

api_passwd: root@321

...................

#Note: Here the yaml file does not using the secret methode. also credential are visible in yaml file. 
