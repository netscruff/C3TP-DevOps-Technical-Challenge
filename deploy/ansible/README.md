# Ansible base directory
This is base directory for running ansible playbooks from.

The ansible.cfg file defines some important configuration like the location
for roles used in the playbook.

The install_roles.yml file contains an ansible-galaxy role for the deployment of Apache Spark.

The site.yml file is the playbook that will launch instances, configure networking,
and bootstrap the instances with the nessesary software for running Apache Spark.
