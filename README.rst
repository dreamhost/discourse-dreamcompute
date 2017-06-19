Discourse ansible playbook
==========================

How to run:

* Copy the vars/\*.yml.example files and create vars/\*.yml files with your
  configs
* Run ansible using ``ansible-playbook -e "env=$environment" site.yml``, For
  example ``ansible-playbook -e "env=prod" site.yml``


Letsencrypt
~~~~~~~~~~~

Letsencrypt requires DNS to be working properly, therefore you must have the
domain you want resolving to the IP of your discourse server. In some cases,
this requires that you run the script 2 times, first with letsencrypt disabled,
then enabled.
