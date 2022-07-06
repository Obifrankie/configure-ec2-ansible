# configure-ec2

This CI script is writing in yaml

It main point of entry is the main.yml file

It has a main workfolw which can be found in the roles/setup/tasks/main.yml

It also has a custom inventory file that allows you define all the machines you want to run this script on

To run this script localy ensure that you have ansile configured locally by running the show command python3 -m pip show ansible

and run the script with the following command ansible-playbook main.yml
