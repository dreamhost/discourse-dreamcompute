Discourse ansible playbook
==========================

How to run:

* Copy the vars/\*.yml.example files and create vars/\*.yml files with your
  configs
* Run ansible using ``ansible-playbook -e "env=$environment" site.yml``, For
  example ``ansible-playbook -e "env=prod" site.yml``
