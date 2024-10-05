
# Welcome to the Ansible-Project wiki!


## The objective of this Ansible playbook is to configure and manage both the web and database servers by applying specific roles to each group of hosts:

### For Web Servers (hosts: web):

* Ensure that the Apache web server is installed, configured, and running by applying the apache role.
* Ensure that firewall rules are applied to secure the web server by applying the firewall role.
* Ensure that backup mechanisms are in place for the web server by applying the backup role.

## For Database Servers (hosts: db):

* Ensure that the MySQL database is installed, configured, and running by applying the mysql role.
* Ensure that firewall rules are applied to secure the database server by applying the firewall role.
* Ensure that backup mechanisms are in place for the database server by applying the backup role.

This playbook focuses on automating the provisioning, security, and backup setup of web and database servers in a consistent and repeatable manner.
