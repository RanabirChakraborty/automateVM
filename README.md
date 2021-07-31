# automateVM
This tool will help you to setup your VM with the help of Ansible.

Please install Ansible in your local system before running the Ansible playbooks.
If you don't have Ansible installed in you local machine, please run the [script](https://github.com/RideToTheRootsPersonal/Ansible_Play/blob/main/ansible.sh) to get it installed easily.

You can change your [host](https://github.com/RanabirChakraborty/automateVM/blob/master/inventory) to play with it.
1. `ansible-playbook create_user.yml` run this to create user in remote host and also add the sshkey. You need to change `users.yml` if you have any other preferences.
2. `ansible-playbook vmupdate.yml` run this to install maven and java in your remote host
