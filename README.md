# slurm_xpaste_ansible
For clonning app from gitlab you need to have gitlabusername and gitlabpassword, change it it playbook.yml or
ansible-playbook -e "gitlabuser=[your username]" -e "gitlabpassword=[your password]"
For installation of all packages you need to install some ansible-galaxy roles and colections they are mentioned in requirements.yml
Also change ip address in hosts.ini 