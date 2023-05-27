# Ansible Collection - alex.docker collection
Documentation for the collection.

# Install
ansible-galaxy collection install git+https://github.com/AlexanderWitteveen/ALEX.Ansible.Docker.git

# Use playbook
vars="{\"args_host\":\"hostname\"}"  
export ANSIBLE_CONFIG=/etc/ansible/ansible.cfg  
ansible-playbook alex.docker.install -vv --extra-vars "$vars"  

