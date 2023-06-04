# Ansible Automates

This project is a collection of Ansible playbooks and roles for automating the setup and configuration of Arch-based and Debian-based Linux systems. 

## Project Structure 

The project is organized into two main directories:
 
1. arch-based: Contains Ansible playbook and roles for configuring Arch-based Linux systems.
2. debian-based: Contains Ansible playbook and roles for configuring Debian-based Linux systems.

Both directories contain an inventory.ini file that defines the hosts on which the playbooks will be executed. Each playbook contains tasks that are defined in roles, which are located in the roles directory. 

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the appropriate directory based on your Linux distribution (arch-based or debian-based).
3. Update the inventory.ini file with the IP addresses or hostnames of your target machines.
4. Run the playbook using the ansible-playbook command.

For example, to run the playbook on Arch-based systems, you would navigate to the arch-based directory and execute the following command:

bash
ansible-playbook -i inventory.ini playbook.yml


Similarly, to run the playbook on Debian-based systems, you would navigate to the debian-based directory and execute the same command.

Note that some of the roles may require additional configuration or variables to be set before they can be executed successfully. Please refer to each role's README file for more information.
