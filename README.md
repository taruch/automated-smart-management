This repo enables you to add 'Ansible and Satellite' templates to your Ansible Automation Platform Controller.

To add the ServiceNow Templates to your Ansible Automation Platform Controller, set up the project in AAP Controller.\
Project Name: Ansible and Satellite Exercise Automation\
Project Organization: Default\
Project Source Control Type: Git\
Project Source Control URL: https://github.com/taruch/automated-smart-management.git\
Project Source Control Branch: aap2-29compat-ruch

Then, you can either create a Setup Template using the 'Ansible and Satellite Exercise Automation' project and the satellite_exercise_template_create.yml template, or run the following using Ansible Navigator:\
ansible-navigator run -mstdout satellite_exercise_template_create.yml -e "user=CONTROLLER_USER" -e "pass=PASSWORD" -e "controller=ANSIBLE_CONTROLLER_HOST_HERE"


Creates the following templates in your controller:
- Run Satellite Exercise 0 
- Run Satellite Exercise 1 
- Run Satellite Exercise 3

