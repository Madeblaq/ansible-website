# My Website

This project is a simple HTML website hosted on an AWS EC2 instance using Ansible for deployment.

## Project Structure

- `inventory`: Inventory file specifying the host(s) for Ansible.
- `site.yml`: Main playbook to configure the web server and deploy the website.
- `index.html`: Simple HTML file for the website.

## Prerequisites

- Ansible installed on the control machine.
- AWS EC2 instance running Ubuntu.
- Personal Access Token (PAT) for GitHub.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Madeblaq/ansible-website.git
   cd ansible-website

2.  Update the inventory file with your Ec2 instance 

 
3. Run the Ansible Playbook
ansible-playbook -i inventory site.yml

##  Usage
Access the website by navigating to the EC2 instance's public IP address in your browser

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your changes


## License
This project is licensed under the MIT License
