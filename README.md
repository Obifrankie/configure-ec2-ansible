# configure-ec2

This CI script is writing in yaml

This script automates the build of an and configuration ec2 and runs custom scripts on configuration

It main point of entry is the main.yml file

This playbook automates the build and configuration of an instance and runs custom scripts on configuration

It has 1 play which is the 
-setup 
The path to this play roles/setup/tasks/main.yml

It also has a custom inventory file that allows you define all the machines you want to run this playbook on

To run this script localy ensure that you have ansile configured locally by running the show command python3 -m pip show ansible

and run the script with the following command ansible-playbook main.yml
